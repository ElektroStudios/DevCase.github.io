# DriveClient.DeleteFileAsync Method (File)
 

Asynchronously permanently deletes a existing file from the Google Drive of the user account.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<string> DeleteFileAsync(
	File file
)
```

**VB**<br />
``` VB
Public Function DeleteFileAsync ( 
	file As File
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim file As File
Dim returnValue As Task(Of String)

returnValue = instance.DeleteFileAsync(file)
```

**C++**<br />
``` C++
public:
Task<String^>^ DeleteFileAsync(
	File^ file
)
```

**F#**<br />
``` F#
member DeleteFileAsync : 
        file : File -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: File<br />A existing file to delete.</dd></dl>

#### Return Value
Type: Task(String)<br />The resulting String.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full)
Dim credential As UserCredential = Await client.AuthorizeAsync()

Dim fileToDelete As Global.Google.Apis.Drive.v3.Data.File = Await GetFileByIdAsync(" File Id. ")
Dim result As String = Await DeleteFileAsync(fileToDelete)

Console.WriteLine(result)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_DeleteFileAsync">DeleteFileAsync Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />