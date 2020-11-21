# DriveClient.GetOwnedFoldersAsync Method 
 

Asynchronously gets the folders stored in the current user account that are owned by him.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<List<File>> GetOwnedFoldersAsync()
```

**VB**<br />
``` VB
Public Function GetOwnedFoldersAsync As Task(Of List(Of File))
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim returnValue As Task(Of List(Of File))

returnValue = instance.GetOwnedFoldersAsync()
```

**C++**<br />
``` C++
public:
Task<List<File^>^>^ GetOwnedFoldersAsync()
```

**F#**<br />
``` F#
member GetOwnedFoldersAsync : unit -> Task<List<File>> 

```


#### Return Value
Type: Task(List(File))<br />The resulting Task(TResult).

## Remarks
<a href="http://developers.google.com/drive/v3/reference/files/get" target="_blank">http://developers.google.com/drive/v3/reference/files/get</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full Or DriveScopes.Metadata)
Dim credential As UserCredential = Await client.AuthorizeAsync()
Dim folders As List(Of Google.Apis.Drive.v3.Data.File) = Await client.GetOwnedFoldersAsync()
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
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_GetOwnedFoldersAsync">GetOwnedFoldersAsync Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />