# OutlookMailClientExperimental Constructor (IntPtr, String, Uri, OutlookMailScopes)
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient">OutlookMailClient</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public OutlookMailClientExperimental(
	IntPtr hWnd,
	string clientId,
	Uri redirectUri,
	OutlookMailScopes scopes
)
```

**VB**<br />
``` VB
Public Sub New ( 
	hWnd As IntPtr,
	clientId As String,
	redirectUri As Uri,
	scopes As OutlookMailScopes
)
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim clientId As String
Dim redirectUri As Uri
Dim scopes As OutlookMailScopes

Dim instance As New OutlookMailClientExperimental(hWnd, clientId, 
	redirectUri, scopes)
```

**C++**<br />
``` C++
public:
OutlookMailClientExperimental(
	IntPtr hWnd, 
	String^ clientId, 
	Uri^ redirectUri, 
	OutlookMailScopes scopes
)
```

**F#**<br />
``` F#
new : 
        hWnd : IntPtr * 
        clientId : string * 
        redirectUri : Uri * 
        scopes : OutlookMailScopes -> OutlookMailClientExperimental
```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />The window handle of the window that will own this <a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient">OutlookMailClient</a> instance.</dd><dt>clientId</dt><dd>Type: System.String<br />The unique identifier of the registered application to use Outlook.com Mail API.</dd><dt>redirectUri</dt><dd>Type: System.Uri<br />The current Outlook.com mail OAuthv2 redirection Uri.</dd><dt>scopes</dt><dd>Type: <a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailScopes">DevCase.ThirdParty.MicrosoftLive.OutlookMailScopes</a><br />The Outlook.com mail OAuthv2 scopes.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailClientExperimental">OutlookMailClientExperimental Class</a><br /><a href="Overload_DevCase_ThirdParty_MicrosoftLive_OutlookMailClientExperimental__ctor">OutlookMailClientExperimental Overload</a><br /><a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive Namespace</a><br />