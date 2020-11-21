# DriveClient.GetFileByIdAsync Method 
 

Asynchronously gets a file stored in the current user account that matches the specified file id.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<File> GetFileByIdAsync(
	string id
)
```

**VB**<br />
``` VB
Public Function GetFileByIdAsync ( 
	id As String
) As Task(Of File)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim id As String
Dim returnValue As Task(Of File)

returnValue = instance.GetFileByIdAsync(id)
```

**C++**<br />
``` C++
public:
Task<File^>^ GetFileByIdAsync(
	String^ id
)
```

**F#**<br />
``` F#
member GetFileByIdAsync : 
        id : string -> Task<File> 

```


#### Parameters
&nbsp;<dl><dt>id</dt><dd>Type: System.String<br />\[Missing <param name="id"/> documentation for "M:DevCase.ThirdParty.Google.Drive.DriveClient.GetFileByIdAsync(System.String)"\]</dd></dl>

#### Return Value
Type: Task(File)<br />The resulting Task(TResult).

## Remarks
<a href="http://developers.google.com/drive/v3/reference/files/get" target="_blank">http://developers.google.com/drive/v3/reference/files/get</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full Or DriveScopes.Metadata)
Dim credential As UserCredential = Await client.AuthorizeAsync()
Dim file As Google.Apis.Drive.v3.Data.File) = Await client.GetFileByIdAsync(" File Id. ")

Dim sb As New Global.System.Text.StringBuilder()
With sb
     .AppendLine(String.Format("Id: {0}", file.Id))
     .AppendLine(String.Format("Owned By Me?: {0}", file.OwnedByMe))
     .AppendLine(String.Format("Name: {0}", file.Name))
     .AppendLine(String.Format("Size: {0}", file.Size))
     .AppendLine(String.Format("Date Created: {0}", file.CreatedTime?.ToString()))
     .AppendLine(String.Format("Url: {0}", If(file.WebContentLink, file.WebViewLink)))
     .AppendLine(String.Format("Parent Folder Ids: {0}", String.Join(",", If(file.Parents, {"nul"}))))
End With
Console.WriteLine(sb.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />