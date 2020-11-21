# OutlookMailClient Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient">OutlookMailClient</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public OutlookMailClient(
	string clientId,
	OutlookMailScopes scopes
)
```

**VB**<br />
``` VB
Public Sub New ( 
	clientId As String,
	scopes As OutlookMailScopes
)
```

**VB Usage**<br />
``` VB Usage
Dim clientId As String
Dim scopes As OutlookMailScopes

Dim instance As New OutlookMailClient(clientId, 
	scopes)
```

**C++**<br />
``` C++
public:
OutlookMailClient(
	String^ clientId, 
	OutlookMailScopes scopes
)
```

**F#**<br />
``` F#
new : 
        clientId : string * 
        scopes : OutlookMailScopes -> OutlookMailClient
```


#### Parameters
&nbsp;<dl><dt>clientId</dt><dd>Type: System.String<br />The unique identifier of the registered application to use Outlook.com Mail API.</dd><dt>scopes</dt><dd>Type: <a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailScopes">DevCase.ThirdParty.MicrosoftLive.OutlookMailScopes</a><br />The Outlook.com mail OAuthv2 scopes.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient">OutlookMailClient Class</a><br /><a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive Namespace</a><br />