# DriveClient.DeleteFileAsync Method (String)
 

Asynchronously permanently deletes a existing file from the Google Drive of the user account.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<string> DeleteFileAsync(
	string fileId
)
```

**VB**<br />
``` VB
Public Function DeleteFileAsync ( 
	fileId As String
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim fileId As String
Dim returnValue As Task(Of String)

returnValue = instance.DeleteFileAsync(fileId)
```

**C++**<br />
``` C++
public:
Task<String^>^ DeleteFileAsync(
	String^ fileId
)
```

**F#**<br />
``` F#
member DeleteFileAsync : 
        fileId : string -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>fileId</dt><dd>Type: System.String<br />The identifier of the existing file to delete.</dd></dl>

#### Return Value
Type: Task(String)<br />The resulting String.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full)
Dim credential As UserCredential = Await client.AuthorizeAsync()

Dim result As String = Await DeleteFileAsync(" Existing File Id. ")

Console.WriteLine(result)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_DeleteFileAsync">DeleteFileAsync Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />