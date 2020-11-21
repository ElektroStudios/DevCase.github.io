# DriveClient.DownloadFile Method (String, String)
 

Downloads the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void DownloadFile(
	string url,
	string dstFilePath
)
```

**VB**<br />
``` VB
Public Sub DownloadFile ( 
	url As String,
	dstFilePath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim url As String
Dim dstFilePath As String

instance.DownloadFile(url, dstFilePath)
```

**C++**<br />
``` C++
public:
void DownloadFile(
	String^ url, 
	String^ dstFilePath
)
```

**F#**<br />
``` F#
member DownloadFile : 
        url : string * 
        dstFilePath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />A Google Drive url that points to the file to download.</dd><dt>dstFilePath</dt><dd>Type: System.String<br />The destination file path where to save the downloaded file.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full Or DriveScopes.Metadata)
Dim credential As UserCredential = client.Authorize()
Dim url As String = "https://drive.google.com/uc?export=download&id=1B04WDF5Df8zYN2NXMlRlMlhYbm8"

client.DownloadFile(url, dstFile)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_DownloadFile">DownloadFile Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />