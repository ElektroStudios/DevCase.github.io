# GmailClient.Authorize Method 
 

Authorizes this instance to use GMail API services.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public UserCredential Authorize()
```

**VB**<br />
``` VB
Public Function Authorize As UserCredential
```

**VB Usage**<br />
``` VB Usage
Dim instance As GmailClient
Dim returnValue As UserCredential

returnValue = instance.Authorize()
```

**C++**<br />
``` C++
public:
UserCredential^ Authorize()
```

**F#**<br />
``` F#
member Authorize : unit -> UserCredential 

```


#### Return Value
Type: UserCredential<br />The resulting UserCredential.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New GmailClient("C:\GoogleSecrets.json", "yourmail@gmail.com", GmailScopes.ReadOnly Or GmailScopes.Modify Or GmailScopes.Send)
Dim credential As UserCredential = client.Authorize()
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Gmail_GmailClient">GmailClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail Namespace</a><br />