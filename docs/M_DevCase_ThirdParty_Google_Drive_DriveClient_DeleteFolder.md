# DriveClient.DeleteFolder Method (File)
 

Permanently deletes a existing folder (including all its files inside) from the Google Drive of the user account.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string DeleteFolder(
	File folder
)
```

**VB**<br />
``` VB
Public Function DeleteFolder ( 
	folder As File
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim folder As File
Dim returnValue As String

returnValue = instance.DeleteFolder(folder)
```

**C++**<br />
``` C++
public:
String^ DeleteFolder(
	File^ folder
)
```

**F#**<br />
``` F#
member DeleteFolder : 
        folder : File -> string 

```


#### Parameters
&nbsp;<dl><dt>folder</dt><dd>Type: File<br />A existing folder to delete.</dd></dl>

#### Return Value
Type: String<br />The resulting String.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full)
Dim credential As UserCredential = client.Authorize()

Dim folderToDelete As Global.Google.Apis.Drive.v3.Data.File = GetFolderById(" Folder Id. ")
Dim result As String = DeleteFFolder(folderToDelete)

Console.WriteLine(result)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_DeleteFolder">DeleteFolder Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />