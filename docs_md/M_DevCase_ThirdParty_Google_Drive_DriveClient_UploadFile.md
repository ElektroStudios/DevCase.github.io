# DriveClient.UploadFile Method (FileInfo, File, String[])
 

Uploads a file in the specified folder.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public KeyValuePair<ResumableUpload, File> UploadFile(
	FileInfo srcFile,
	File dstFile,
	params string[] parentFolderIds
)
```

**VB**<br />
``` VB
Public Function UploadFile ( 
	srcFile As FileInfo,
	dstFile As File,
	ParamArray parentFolderIds As String()
) As KeyValuePair(Of ResumableUpload, File)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim srcFile As FileInfo
Dim dstFile As File
Dim parentFolderIds As String()
Dim returnValue As KeyValuePair(Of ResumableUpload, File)

returnValue = instance.UploadFile(srcFile, 
	dstFile, parentFolderIds)
```

**C++**<br />
``` C++
public:
KeyValuePair<ResumableUpload^, File^> UploadFile(
	FileInfo^ srcFile, 
	File^ dstFile, 
	... array<String^>^ parentFolderIds
)
```

**F#**<br />
``` F#
member UploadFile : 
        srcFile : FileInfo * 
        dstFile : File * 
        parentFolderIds : string[] -> KeyValuePair<ResumableUpload, File> 

```


#### Parameters
&nbsp;<dl><dt>srcFile</dt><dd>Type: System.IO.FileInfo<br />The source file to upload.</dd><dt>dstFile</dt><dd>Type: File<br />The metadata of the file being uploaded. 

 In the metadata you can specify values like the destination filename, description, folder destination, etc...</dd><dt>parentFolderIds</dt><dd>Type: System.String[]<br />The identifier of the parent folder(s) where to upload the file. 

 This paramenter can be empty (nul).</dd></dl>

#### Return Value
Type: KeyValuePair(ResumableUpload, File)<br />The resulting KeyValuePair(TKey, TValue).

## Examples
This is a code example. 
**VB**<br />
``` VB
Private Sub UploadFile()

   Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full)
   Dim credential As UserCredential = client.Authorize()

   Dim srcFile As New FileInfo("C:\File.ext")
   Dim dstFolder As Google.Apis.Drive.v3.Data.File = client.GetFoldersByName("Folder Name").Single()

    Dim dstFile As New Global.Google.Apis.Drive.v3.Data.File
    With dstFile
        .Name = "New File Name"
        .Description = "File Description"
        .Parents = {dstFolder.Id}
    End With

   Dim result As KeyValuePair(Of Google.Apis.Upload.ResumableUpload, Google.Apis.Drive.v3.Data.File) =
       client.UploadFile(srcFile, dstFile, dstFolder.Id)

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
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_UploadFile">UploadFile Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />