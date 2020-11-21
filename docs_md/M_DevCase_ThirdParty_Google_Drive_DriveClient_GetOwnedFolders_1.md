# DriveClient.GetOwnedFolders Method (Func(File, Boolean))
 

Gets the folders stored in the current user account that are owned by him and matches the specified search criteria.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public List<File> GetOwnedFolders(
	Func<File, bool> predicate
)
```

**VB**<br />
``` VB
Public Function GetOwnedFolders ( 
	predicate As Func(Of File, Boolean)
) As List(Of File)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim predicate As Func(Of File, Boolean)
Dim returnValue As List(Of File)

returnValue = instance.GetOwnedFolders(predicate)
```

**C++**<br />
``` C++
public:
List<File^>^ GetOwnedFolders(
	Func<File^, bool>^ predicate
)
```

**F#**<br />
``` F#
member GetOwnedFolders : 
        predicate : Func<File, bool> -> List<File> 

```


#### Parameters
&nbsp;<dl><dt>predicate</dt><dd>Type: System.Func(File, Boolean)<br />\[Missing <param name="predicate"/> documentation for "M:DevCase.ThirdParty.Google.Drive.DriveClient.GetOwnedFolders(System.Func{Google.Apis.Drive.v3.Data.File,System.Boolean})"\]</dd></dl>

#### Return Value
Type: List(File)<br />The resulting Task(TResult).

## Remarks
<a href="http://developers.google.com/drive/v3/reference/files/get" target="_blank">http://developers.google.com/drive/v3/reference/files/get</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full Or DriveScopes.Metadata)
Dim credential As UserCredential = client.Authorize()
Dim predicate As Func(Of Google.Apis.Drive.v3.Data.File, Boolean) = 
    Function(f As Google.Apis.Drive.v3.Data.File) f.Name.Equals("My Folder Name", StringComparison.OrdinalIgnoreCase)
Dim folders As List(Of Google.Apis.Drive.v3.Data.File) = client.GetOwnedFolders(predicate)
Dim folderCount As Integer

For Each folder As Google.Apis.Drive.v3.Data.File In folders
    Dim sb As New Global.System.Text.StringBuilder()
    With sb
        .AppendLine(String.Format("Count: {0}", Interlocked.Increment(folderCount)))
        .AppendLine(String.Format("Id: {0}", folder.Id))
        .AppendLine(String.Format("Name: {0}", folder.Name))
        .AppendLine(String.Format("Size: {0}", folder.Size))
        .AppendLine(String.Format("Date Created: {0}", folder.CreatedTime?.ToString()))
        .AppendLine(String.Format("Url: {0}", If(folder.WebContentLink, folder.WebViewLink)))
        .AppendLine(String.Format("Parent Folder Ids: {0}", String.Join(",", If(folder.Parents, {"nul"}))))
    End With
    Console.WriteLine(sb.ToString())
Next file
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_GetOwnedFolders">GetOwnedFolders Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />