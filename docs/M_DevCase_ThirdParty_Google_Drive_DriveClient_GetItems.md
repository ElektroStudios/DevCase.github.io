# DriveClient.GetItems Method 
 

Gets all the files and folders stored in the current user account.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public List<File> GetItems()
```

**VB**<br />
``` VB
Public Function GetItems As List(Of File)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim returnValue As List(Of File)

returnValue = instance.GetItems()
```

**C++**<br />
``` C++
public:
List<File^>^ GetItems()
```

**F#**<br />
``` F#
member GetItems : unit -> List<File> 

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
Dim items As List(Of Google.Apis.Drive.v3.Data.File) = client.GetItems()
Dim itemCount As Integer

For Each item As Google.Apis.Drive.v3.Data.File In items
    Dim sb As New Global.System.Text.StringBuilder()
    With sb
        .AppendLine(String.Format("Count: {0}", Interlocked.Increment(itemCount)))
        .AppendLine(String.Format("Id: {0}", item.Id))
        .AppendLine(String.Format("Is Folder?: {0}", item.MimeType.Contains("folder")))
        .AppendLine(String.Format("Owned By Me?: {0}", item.OwnedByMe))
        .AppendLine(String.Format("Name: {0}", item.Name))
        .AppendLine(String.Format("Size: {0}", item.Size))
        .AppendLine(String.Format("Date Created: {0}", item.CreatedTime?.ToString()))
        .AppendLine(String.Format("Url: {0}", If(item.WebContentLink, item.WebViewLink)))
        .AppendLine(String.Format("Parent Folder Ids: {0}", String.Join(",", If(item.Parents, {"nul"}))))
    End With
    Console.WriteLine(sb.ToString())
Next file
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_GetItems">GetItems Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />