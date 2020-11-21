# DriveClient.GetFolderById Method 
 

Gets a folder stored in the current user account that matches the specified folder id.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public File GetFolderById(
	string id
)
```

**VB**<br />
``` VB
Public Function GetFolderById ( 
	id As String
) As File
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim id As String
Dim returnValue As File

returnValue = instance.GetFolderById(id)
```

**C++**<br />
``` C++
public:
File^ GetFolderById(
	String^ id
)
```

**F#**<br />
``` F#
member GetFolderById : 
        id : string -> File 

```


#### Parameters
&nbsp;<dl><dt>id</dt><dd>Type: System.String<br />\[Missing <param name="id"/> documentation for "M:DevCase.ThirdParty.Google.Drive.DriveClient.GetFolderById(System.String)"\]</dd></dl>

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
Dim folder As Google.Apis.Drive.v3.Data.File) = client.GetFolderById(" Folder Id. ")

Dim sb As New Global.System.Text.StringBuilder()
With sb
     .AppendLine(String.Format("Id: {0}", folder.Id))
     .AppendLine(String.Format("Owned By Me?: {0}", folder.OwnedByMe))
     .AppendLine(String.Format("Name: {0}", folder.Name))
     .AppendLine(String.Format("Size: {0}", folder.Size))
     .AppendLine(String.Format("Date Created: {0}", folder.CreatedTime?.ToString()))
     .AppendLine(String.Format("Url: {0}", If(folder.WebContentLink, folder.WebViewLink)))
     .AppendLine(String.Format("Parent Folder Ids: {0}", String.Join(",", If(folder.Parents, {"nul"}))))
End With
Console.WriteLine(sb.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />