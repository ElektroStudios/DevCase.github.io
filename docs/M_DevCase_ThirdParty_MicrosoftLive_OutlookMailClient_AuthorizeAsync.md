# OutlookMailClient.AuthorizeAsync Method 
 

Authorizes this instance to use Microsoft Outlook Mail services.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<AuthenticationResult> AuthorizeAsync()
```

**VB**<br />
``` VB
Public Function AuthorizeAsync As Task(Of AuthenticationResult)
```

**VB Usage**<br />
``` VB Usage
Dim instance As OutlookMailClient
Dim returnValue As Task(Of AuthenticationResult)

returnValue = instance.AuthorizeAsync()
```

**C++**<br />
``` C++
public:
Task<AuthenticationResult^>^ AuthorizeAsync()
```

**F#**<br />
``` F#
member AuthorizeAsync : unit -> Task<AuthenticationResult> 

```


#### Return Value
Type: Task(AuthenticationResult)<br />The resulting Task(TResult).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim outlookClient As New OutlookMailClient("YOUR CLIENT ID", OutlookMailScopes.ReadWrite Or OutlookMailScopes.Send)
Await outlookClient.AuthorizeAsync()
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient">OutlookMailClient Class</a><br /><a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive Namespace</a><br />