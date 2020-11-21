# DriveClient.DeleteFolderAsync Method (String)
 

Asynchronously permanently deletes a existing folder (including all its files inside) from the Google Drive of the user account.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<string> DeleteFolderAsync(
	string folderId
)
```

**VB**<br />
``` VB
Public Function DeleteFolderAsync ( 
	folderId As String
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim folderId As String
Dim returnValue As Task(Of String)

returnValue = instance.DeleteFolderAsync(folderId)
```

**C++**<br />
``` C++
public:
Task<String^>^ DeleteFolderAsync(
	String^ folderId
)
```

**F#**<br />
``` F#
member DeleteFolderAsync : 
        folderId : string -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>folderId</dt><dd>Type: System.String<br />The identifier of the existing folder to delete.</dd></dl>

#### Return Value
Type: Task(String)<br />The resulting String.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.Full)
Dim credential As UserCredential = Await client.AuthorizeAsync()

Dim result As String = Await DeleteFolderAsync(" Existing Folder Id. ")

Console.WriteLine(result)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Drive_DriveClient_DeleteFolderAsync">DeleteFolderAsync Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />