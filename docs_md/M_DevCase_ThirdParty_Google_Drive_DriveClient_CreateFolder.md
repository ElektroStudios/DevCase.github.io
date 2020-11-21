# DriveClient.CreateFolder Method 
 

Creates a new folder in the Google Drive of the user account.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public File CreateFolder(
	string dstName,
	params string[] parentFolderIds
)
```

**VB**<br />
``` VB
Public Function CreateFolder ( 
	dstName As String,
	ParamArray parentFolderIds As String()
) As File
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim dstName As String
Dim parentFolderIds As String()
Dim returnValue As File

returnValue = instance.CreateFolder(dstName, 
	parentFolderIds)
```

**C++**<br />
``` C++
public:
File^ CreateFolder(
	String^ dstName, 
	... array<String^>^ parentFolderIds
)
```

**F#**<br />
``` F#
member CreateFolder : 
        dstName : string * 
        parentFolderIds : string[] -> File 

```


#### Parameters
&nbsp;<dl><dt>dstName</dt><dd>Type: System.String<br />The name of the folder being created.</dd><dt>parentFolderIds</dt><dd>Type: System.String[]<br />The identifier of the parent folder(s) where to create the new folder. 

 This paramenter can be empty (nul).</dd></dl>

#### Return Value
Type: File<br />The resulting File.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full)
Dim credential As UserCredential = client.Authorize()

Dim dstParentFolder As Global.Google.Apis.Drive.v3.Data.File = client.GetFoldersByName("Parent Folder Name").Single()
Dim createdFolder As Global.Google.Apis.Drive.v3.Data.File = client.CreateFolder("Folder Name", dstParentFolder.Id)

Dim sb As New Global.System.Text.StringBuilder()
With sb
    .AppendLine(String.Format("Id: {0}", createdFolder.Id))
    .AppendLine(String.Format("Name: {0}", createdFolder.Name))
    .AppendLine(String.Format("Date Created: {0}", createdFolder.CreatedTime?.ToString()))
    .AppendLine(String.Format("Url: {0}", If(createdFolder.WebContentLink, createdFolder.WebViewLink)))
    .AppendLine(String.Format("Parent Folder Ids: {0}", String.Join(",", If(createdFolder.Parents, {"nul"}))))
End With
Console.WriteLine(sb.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />