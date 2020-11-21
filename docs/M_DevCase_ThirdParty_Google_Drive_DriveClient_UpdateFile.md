# DriveClient.UpdateFile Method (FileInfo, File)
 

Updates (replaces) a existing file in the specified folder.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public KeyValuePair<ResumableUpload, File> UpdateFile(
	FileInfo srcFile,
	File dstFile
)
```

**VB**<br />
``` VB
Public Function UpdateFile ( 
	srcFile As FileInfo,
	dstFile As File
) As KeyValuePair(Of ResumableUpload, File)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim srcFile As FileInfo
Dim dstFile As File
Dim returnValue As KeyValuePair(Of ResumableUpload, File)

returnValue = instance.UpdateFile(srcFile, 
	dstFile)
```

**C++**<br />
``` C++
public:
KeyValuePair<ResumableUpload^, File^> UpdateFile(
	FileInfo^ srcFile, 
	File^ dstFile
)
```

**F#**<br />
``` F#
member UpdateFile : 
        srcFile : FileInfo * 
        dstFile : File -> KeyValuePair<ResumableUpload, File> 

```


#### Parameters
&nbsp;<dl><dt>srcFile</dt><dd>Type: System.IO.FileInfo<br />The source file to upload.</dd><dt>dstFile</dt><dd>Type: File<br />The metadata of the existing file being updated.</dd></dl>

#### Return Value
Type: KeyValuePair(ResumableUpload, File)<br />The resulting KeyValuePair(TKey, TValue).

## Examples
This is a code example. 
**VB**<br />
``` VB
Private Sub UpdateFile()

   Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full)
   Dim credential As UserCredential = client.Authorize()

   Dim srcFile As New FileInfo("C:\File.ext")
   Dim dstFile As Google.Apis.Drive.v3.Data.File = client.GetFilesByName("File to update.ext").Single()

   Dim result As KeyValuePair(Of Google.Apis.Upload.ResumableUpload, Google.Apis.Drive.v3.Data.File) =
       client.UpdateFile(srcFile, dstFile)

   Dim upload As Global.Google.Apis.Upload.ResumableUpload = result.Key

   Select Case upload.GetProgress().Status

       Case Global.Google.Apis.Upload.UploadStatus.Failed
           Console.WriteLine("Upload Failed.")
           ' To-Do: Retry/Resume Upload?:
           ' upload.Upload()
           ' upload.Resume()

       Case Global.Google.Apis.Upload.UploadStatus.Completed
           Dim dstFile As Global.Google.Apis.Upload.ResumableUpload = result.Value
           Dim sb As New Global.System.Text.StringBuilder()
           With sb
               .AppendLine(String.Format("Id: {0}", dstFile.Id))
               .AppendLine(String.Format("Name: {0}", dstFile.Name))
               .AppendLine(String.Format("Size: {0}", dstFile.Size))
               .AppendLine(String.Format("MIME type: {0}", dstFile.MimeType))
               .AppendLine(String.Format("Date Created: {0}", dstFile.CreatedTime?.ToString()))
               .AppendLine(String.Format("Url: {0}", If(dstFile.WebContentLink, dstFile.WebViewLink)))
               .AppendLine(String.Format("Parent Folder Ids: {0}", String.Join(",", If(dstFile.Parents, {"nul"}))))
           End With
       Console.WriteLine(sb.ToString())

   End Select

End Sub
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_UpdateFile">UpdateFile Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />