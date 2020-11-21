# DriveClient.DownloadFile Method (File, String)
 

Downloads the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void DownloadFile(
	File srcFile,
	string dstFilePath
)
```

**VB**<br />
``` VB
Public Sub DownloadFile ( 
	srcFile As File,
	dstFilePath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim srcFile As File
Dim dstFilePath As String

instance.DownloadFile(srcFile, dstFilePath)
```

**C++**<br />
``` C++
public:
void DownloadFile(
	File^ srcFile, 
	String^ dstFilePath
)
```

**F#**<br />
``` F#
member DownloadFile : 
        srcFile : File * 
        dstFilePath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>srcFile</dt><dd>Type: File<br />The source file to download.</dd><dt>dstFilePath</dt><dd>Type: System.String<br />The destination file path where to save the downloaded file.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full Or DriveScopes.Metadata)
Dim credential As UserCredential = client.Authorize()
Dim file As Google.Apis.Drive.v3.Data.File = client.GetFileById(" File Id. ")

client.DownloadFile(srcFile, dstFile)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_DownloadFile">DownloadFile Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />