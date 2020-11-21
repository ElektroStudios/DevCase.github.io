# DriveClient.DeleteFile Method (File)
 

Permanently deletes a existing file from the Google Drive of the user account.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string DeleteFile(
	File file
)
```

**VB**<br />
``` VB
Public Function DeleteFile ( 
	file As File
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim file As File
Dim returnValue As String

returnValue = instance.DeleteFile(file)
```

**C++**<br />
``` C++
public:
String^ DeleteFile(
	File^ file
)
```

**F#**<br />
``` F#
member DeleteFile : 
        file : File -> string 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: File<br />A existing file to delete.</dd></dl>

#### Return Value
Type: String<br />The resulting String.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full)
Dim credential As UserCredential = client.Authorize()

Dim fileToDelete As Global.Google.Apis.Drive.v3.Data.File = GetFileById(" File Id. ")
Dim result As String = DeleteFile(fileToDelete)

Console.WriteLine(result)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_DeleteFile">DeleteFile Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />