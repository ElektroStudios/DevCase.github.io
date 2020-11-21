# DriveClient.GetOwnedFiles Method 
 

Gets the files stored in the current user account that are owned by him.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public List<File> GetOwnedFiles()
```

**VB**<br />
``` VB
Public Function GetOwnedFiles As List(Of File)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim returnValue As List(Of File)

returnValue = instance.GetOwnedFiles()
```

**C++**<br />
``` C++
public:
List<File^>^ GetOwnedFiles()
```

**F#**<br />
``` F#
member GetOwnedFiles : unit -> List<File> 

```


#### Return Value
Type: List(File)<br />The resulting List(T).

## Remarks
<a href="http://developers.google.com/drive/v3/reference/files/get" target="_blank">http://developers.google.com/drive/v3/reference/files/get</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full Or DriveScopes.Metadata)
Dim credential As UserCredential = client.Authorize()
Dim files As List(Of Google.Apis.Drive.v3.Data.File) = client.GetOwnedFiles()
Dim fileCount As Integer

For Each file As Google.Apis.Drive.v3.Data.File In files
    Dim sb As New Global.System.Text.StringBuilder()
    With sb
        .AppendLine(String.Format("Count: {0}", Interlocked.Increment(fileCount)))
        .AppendLine(String.Format("Id: {0}", file.Id))
        .AppendLine(String.Format("Name: {0}", file.Name))
        .AppendLine(String.Format("Size: {0}", file.Size))
        .AppendLine(String.Format("Date Created: {0}", file.CreatedTime?.ToString()))
        .AppendLine(String.Format("Url: {0}", If(file.WebContentLink, file.WebViewLink)))
        .AppendLine(String.Format("Parent Folder Ids: {0}", String.Join(",", If(file.Parents, {"nul"}))))
    End With
    Console.WriteLine(sb.ToString())
Next file
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_GetOwnedFiles">GetOwnedFiles Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />