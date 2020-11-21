# DevWebClient.CookiesEnabled Property 
 

Gets or sets a value indicating whether cookies are enabled. 

 Default value is `false` (`False` in Visual Basic).

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool CookiesEnabled { get; set; }
```

**VB**<br />
``` VB
Public Property CookiesEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevWebClient
Dim value As Boolean

value = instance.CookiesEnabled

instance.CookiesEnabled = value
```

**C++**<br />
``` C++
public:
property bool CookiesEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member CookiesEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if cookies are enabled; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_NET_DevWebClient">DevWebClient Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />