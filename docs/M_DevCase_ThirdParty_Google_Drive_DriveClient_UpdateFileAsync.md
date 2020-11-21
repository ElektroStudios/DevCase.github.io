# DriveClient.UpdateFileAsync Method (FileInfo, File, Action(IUploadProgress), CancellationToken)
 

Asynchronously updates (replaces) a existing file in the specified folder.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<KeyValuePair<ResumableUpload, File>> UpdateFileAsync(
	FileInfo srcFile,
	File dstFile,
	Action<IUploadProgress> progressHandler,
	CancellationToken cancellationToken
)
```

**VB**<br />
``` VB
Public Function UpdateFileAsync ( 
	srcFile As FileInfo,
	dstFile As File,
	progressHandler As Action(Of IUploadProgress),
	cancellationToken As CancellationToken
) As Task(Of KeyValuePair(Of ResumableUpload, File))
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim srcFile As FileInfo
Dim dstFile As File
Dim progressHandler As Action(Of IUploadProgress)
Dim cancellationToken As CancellationToken
Dim returnValue As Task(Of KeyValuePair(Of ResumableUpload, File))

returnValue = instance.UpdateFileAsync(srcFile, 
	dstFile, progressHandler, cancellationToken)
```

**C++**<br />
``` C++
public:
Task<KeyValuePair<ResumableUpload^, File^>>^ UpdateFileAsync(
	FileInfo^ srcFile, 
	File^ dstFile, 
	Action<IUploadProgress^>^ progressHandler, 
	CancellationToken cancellationToken
)
```

**F#**<br />
``` F#
member UpdateFileAsync : 
        srcFile : FileInfo * 
        dstFile : File * 
        progressHandler : Action<IUploadProgress> * 
        cancellationToken : CancellationToken -> Task<KeyValuePair<ResumableUpload, File>> 

```


#### Parameters
&nbsp;<dl><dt>srcFile</dt><dd>Type: System.IO.FileInfo<br />The source file to upload.</dd><dt>dstFile</dt><dd>Type: File<br />The metadata of the existing file being updated.</dd><dt>progressHandler</dt><dd>Type: System.Action(IUploadProgress)<br />A event handler that will receive progress changes of the upload operation.</dd><dt>cancellationToken</dt><dd>Type: System.Threading.CancellationToken<br />A cancellation token to cancel the upload operation.</dd></dl>

#### Return Value
Type: Task(KeyValuePair(ResumableUpload, File))<br />The resulting Task(TResult).

## Examples
This is a code example. 
**VB**<br />
``` VB
Private Async Sub UpdateFile()

   Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full)
   Dim credential As UserCredential = Await client.AuthorizeAsync()

   Dim srcFile As New FileInfo("C:\File.ext")
   Dim dstFile As Google.Apis.Drive.v3.Data.File = client.GetFilesByName("File to update.ext").Single()

   Dim result As KeyValuePair(Of Google.Apis.Upload.ResumableUpload, Google.Apis.Drive.v3.Data.File) =
       Await client.UpdateFileAsync(srcFile, dstFile, AddressOf Me.Upload_ProgressChanged, Nothing)

    Dim sb As New Global.System.Text.StringBuilder()
    With sb
        .AppendLine(String.Format("Id: {0}", result.Value.Id))
        .AppendLine(String.Format("Name: {0}", result.Value.Name))
        .AppendLine(String.Format("Size: {0}", result.Value.Size))
        .AppendLine(String.Format("MIME type: {0}", result.Value.MimeType))
        .AppendLine(String.Format("Date Created: {0}", result.Value.CreatedTime?.ToString()))
        .AppendLine(String.Format("Url: {0}", If(result.Value.WebContentLink, result.Value.WebViewLink)))
        .AppendLine(String.Format("Parent Folder Ids: {0}", String.Join(",", If(result.Value.Parents, {"nul"}))))
    End With
    Console.WriteLine(sb.ToString())

End Sub

Public Sub Upload_ProgressChanged(ByVal e As Google.Apis.Upload.IUploadProgress)

    Select Case e.Status

        Case Google.Apis.Upload.UploadStatus.Starting
            Console.WriteLine("Starting upload...")

        Case Google.Apis.Upload.UploadStatus.Uploading
            Console.WriteLine("Bytes sent: {0}", e.BytesSent)

        Case Google.Apis.Upload.UploadStatus.Completed
            Console.WriteLine("Upload completed.")

        Case Google.Apis.Upload.UploadStatus.Failed
            Console.WriteLine("Upload failed. Reason: {0}", e.Exception.Message)

        Case Else
            ' Do Nothing.

    End Select

End Sub
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_UpdateFileAsync">UpdateFileAsync Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />