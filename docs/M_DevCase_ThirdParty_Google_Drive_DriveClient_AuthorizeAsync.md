# DriveClient.AuthorizeAsync Method 
 

Authorizes this instance to use Google Drive API services.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<UserCredential> AuthorizeAsync()
```

**VB**<br />
``` VB
Public Function AuthorizeAsync As Task(Of UserCredential)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveClient
Dim returnValue As Task(Of UserCredential)

returnValue = instance.AuthorizeAsync()
```

**C++**<br />
``` C++
public:
Task<UserCredential^>^ AuthorizeAsync()
```

**F#**<br />
``` F#
member AuthorizeAsync : unit -> Task<UserCredential> 

```


#### Return Value
Type: Task(UserCredential)<br />The resulting Task(TResult).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New DriveClient("C:\GoogleSecrets.json", "yourmail@gmail.com", DriveScopes.ReadOnly Or DriveScopes.Modify Or DriveScopes.Send)
Dim credential As UserCredential = Await client.AuthorizeAsync()
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Drive_DriveClient">DriveClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Drive">DevCase.ThirdParty.Google.Drive Namespace</a><br />