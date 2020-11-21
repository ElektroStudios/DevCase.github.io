# OutlookMailClient.ClientId Property 
 

Gets the unique identifier of the registered application to use Outlook.com Mail API.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string ClientId { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property ClientId As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As OutlookMailClient
Dim value As String

value = instance.ClientId

```

**C++**<br />
``` C++
public:
property String^ ClientId {
	String^ get ();
}
```

**F#**<br />
``` F#
member ClientId : string with get

```


#### Property Value
Type: String<br />The unique identifier of the registered application to use Outlook.com Mail API.

## Remarks
You can get an API key at Microsoft's Application Registration Portal: 

<a href="http://apps.dev.microsoft.com/#/appList" target="_blank">http://apps.dev.microsoft.com/#/appList</a>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient">OutlookMailClient Class</a><br /><a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive Namespace</a><br />