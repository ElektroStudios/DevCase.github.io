# DriveClient.DownloadFileAsync Method (Uri, String)
 

Asynchronously downloads the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<IDownloadProgress> DownloadFileAsync(
	Uri uri,
	string dstFilePath
)
```

**VB**<br />
``` VB
Public Function DownloadFileAsync ( 
	uri As Uri,
	dstFilePath As String
) As Task(Of IDownloadProgress)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim uri As Uri
Dim dstFilePath As String
Dim returnValue As Task(Of IDownloadProgress)

returnValue = instance.DownloadFileAsync(uri, 
	dstFilePath)
```

**C++**<br />
``` C++
public:
Task<IDownloadProgress^>^ DownloadFileAsync(
	Uri^ uri, 
	String^ dstFilePath
)
```

**F#**<br />
``` F#
member DownloadFileAsync : 
        uri : Uri * 
        dstFilePath : string -> Task<IDownloadProgress> 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />A Google Drive Uri that points to the file to download.</dd><dt>dstFilePath</dt><dd>Type: System.String<br />The destination file path where to save the downloaded file.</dd></dl>

#### Return Value
Type: Task(IDownloadProgress)<br />The resulting Task(TResult).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full Or DriveScopes.Metadata)
Dim credential As UserCredential = Await client.AuthorizeAsync()
Dim uri As New Uri("https://drive.google.com/uc?export=download&id=1B04WDF5Df8zYN2NXMlRlMlhYbm8")

Dim progress As Google.Apis.Download.IDownloadProgress = Await client.DownloadFileAsync(url, dstFile)
Dim status As Google.Apis.Download.DownloadStatus = progress.Status
Console.WriteLine(status)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_DownloadFileAsync">DownloadFileAsync Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />