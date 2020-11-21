# DriveClient.CreateFolderAsync Method 
 

Asynchronously creates a new folder in the Google Drive of the user account.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<File> CreateFolderAsync(
	string dstName,
	params string[] parentFolderIds
)
```

**VB**<br />
``` VB
Public Function CreateFolderAsync ( 
	dstName As String,
	ParamArray parentFolderIds As String()
) As Task(Of File)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim dstName As String
Dim parentFolderIds As String()
Dim returnValue As Task(Of File)

returnValue = instance.CreateFolderAsync(dstName, 
	parentFolderIds)
```

**C++**<br />
``` C++
public:
Task<File^>^ CreateFolderAsync(
	String^ dstName, 
	... array<String^>^ parentFolderIds
)
```

**F#**<br />
``` F#
member CreateFolderAsync : 
        dstName : string * 
        parentFolderIds : string[] -> Task<File> 

```


#### Parameters
&nbsp;<dl><dt>dstName</dt><dd>Type: System.String<br />The name of the folder being created.</dd><dt>parentFolderIds</dt><dd>Type: System.String[]<br />The identifier of the parent folder(s) where to create the new folder. 

 This paramenter can be empty (nul).</dd></dl>

#### Return Value
Type: Task(File)<br />The resulting File.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full)
Dim credential As UserCredential = Await client.AuthorizeAsync()

Dim dstParentFolder As Global.Google.Apis.Drive.v3.Data.File = client.GetFoldersByName("Parent Folder Name").Single()
Dim createdFolder As Global.Google.Apis.Drive.v3.Data.File = Await client.CreateFolderAsync("Folder Name", dstParentFolder.Id)

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