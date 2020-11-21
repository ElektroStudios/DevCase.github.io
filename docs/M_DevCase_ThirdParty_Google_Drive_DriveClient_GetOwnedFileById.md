# DriveClient.GetOwnedFileById Method 
 

Gets a file stored in the current user account that is owned by him and matches the specified file id.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public File GetOwnedFileById(
	string id
)
```

**VB**<br />
``` VB
Public Function GetOwnedFileById ( 
	id As String
) As File
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim id As String
Dim returnValue As File

returnValue = instance.GetOwnedFileById(id)
```

**C++**<br />
``` C++
public:
File^ GetOwnedFileById(
	String^ id
)
```

**F#**<br />
``` F#
member GetOwnedFileById : 
        id : string -> File 

```


#### Parameters
&nbsp;<dl><dt>id</dt><dd>Type: System.String<br />\[Missing <param name="id"/> documentation for "M:DevCase.ThirdParty.Google.Drive.DriveClient.GetOwnedFileById(System.String)"\]</dd></dl>

#### Return Value
Type: File<br />The resulting File.

## Remarks
<a href="http://developers.google.com/drive/v3/reference/files/get" target="_blank">http://developers.google.com/drive/v3/reference/files/get</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full Or DriveScopes.Metadata)
Dim credential As UserCredential = client.Authorize()
Dim file As Google.Apis.Drive.v3.Data.File) = client.GetOwnedFileById(" File Id. ")

Dim sb As New Global.System.Text.StringBuilder()
With sb
     .AppendLine(String.Format("Id: {0}", file.Id))
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