# DriveClient.DownloadFileAsync Method (File, String, Action(IDownloadProgress), CancellationToken)
 

Asynchronously downloads the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<IDownloadProgress> DownloadFileAsync(
	File srcFile,
	string dstFilePath,
	Action<IDownloadProgress> progressHandler,
	CancellationToken cancellationToken
)
```

**VB**<br />
``` VB
Public Function DownloadFileAsync ( 
	srcFile As File,
	dstFilePath As String,
	progressHandler As Action(Of IDownloadProgress),
	cancellationToken As CancellationToken
) As Task(Of IDownloadProgress)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim srcFile As File
Dim dstFilePath As String
Dim progressHandler As Action(Of IDownloadProgress)
Dim cancellationToken As CancellationToken
Dim returnValue As Task(Of IDownloadProgress)

returnValue = instance.DownloadFileAsync(srcFile, 
	dstFilePath, progressHandler, cancellationToken)
```

**C++**<br />
``` C++
public:
Task<IDownloadProgress^>^ DownloadFileAsync(
	File^ srcFile, 
	String^ dstFilePath, 
	Action<IDownloadProgress^>^ progressHandler, 
	CancellationToken cancellationToken
)
```

**F#**<br />
``` F#
member DownloadFileAsync : 
        srcFile : File * 
        dstFilePath : string * 
        progressHandler : Action<IDownloadProgress> * 
        cancellationToken : CancellationToken -> Task<IDownloadProgress> 

```


#### Parameters
&nbsp;<dl><dt>srcFile</dt><dd>Type: File<br />The source file to download.</dd><dt>dstFilePath</dt><dd>Type: System.String<br />The destination file path where to save the downloaded file.</dd><dt>progressHandler</dt><dd>Type: System.Action(IDownloadProgress)<br />A event handler that will receive progress changes of the download operation.</dd><dt>cancellationToken</dt><dd>Type: System.Threading.CancellationToken<br />A cancellation token to cancel the download operation.</dd></dl>

#### Return Value
Type: Task(IDownloadProgress)<br />The resulting Task(TResult).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full Or DriveScopes.Metadata)
Dim credential As UserCredential = Await client.AuthorizeAsync()
Dim file As Google.Apis.Drive.v3.Data.File = Await client.GetFileByIdAsync(" File Id. ")

Dim progress As Google.Apis.Download.IDownloadProgress =
    Await client.DownloadFileAsync(srcFile, dstFile, AddressOf Me.Download_ProgressChanged, Nothing)

Public Sub Download_ProgressChanged(ByVal e As Google.Apis.Download.IDownloadProgress)

    Select Case e.Status

        Case Google.Apis.Download.DownloadStatus.NotStarted
            Console.WriteLine("Starting download...")

        Case Google.Apis.Download.DownloadStatus.Downloading
            Console.WriteLine("Bytes downloaded: {0}", e.BytesDownloaded)

        Case Google.Apis.Download.DownloadStatus.Completed
            Console.WriteLine("Download completed.")

        Case Google.Apis.Download.DownloadStatus.Failed
            Console.WriteLine("Download failed. Reason: {0}", e.Exception.Message)

        Case Else
            ' Do Nothing.

    End Select

End Sub
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_DownloadFileAsync">DownloadFileAsync Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />