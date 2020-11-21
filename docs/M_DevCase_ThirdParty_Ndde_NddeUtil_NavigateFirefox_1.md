# NddeUtil.NavigateFirefox Method (Uri, Boolean)
 

Navigates to the specified Url in the running Firefox process.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Ndde">DevCase.ThirdParty.Ndde</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void NavigateFirefox(
	Uri uri,
	bool openInNewwindow = false
)
```

**VB**<br />
``` VB
Public Shared Sub NavigateFirefox ( 
	uri As Uri,
	Optional openInNewwindow As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim uri As Uri
Dim openInNewwindow As BooleanNddeUtil.NavigateFirefox(uri, openInNewwindow)
```

**C++**<br />
``` C++
public:
static void NavigateFirefox(
	Uri^ uri, 
	bool openInNewwindow = false
)
```

**F#**<br />
``` F#
static member NavigateFirefox : 
        uri : Uri * 
        ?openInNewwindow : bool 
(* Defaults:
        let _openInNewwindow = defaultArg openInNewwindow false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />The Url to navigate.</dd><dt>openInNewwindow (Optional)</dt><dd>Type: System.Boolean<br />\[Missing <param name="openInNewwindow"/> documentation for "M:DevCase.ThirdParty.Ndde.NddeUtil.NavigateFirefox(System.Uri,System.Boolean)"\]</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
NavigateFirefox(New Uri("http://www.mozilla.org"), openInNewwindow:=False)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Ndde_NddeUtil">NddeUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_Ndde_NddeUtil_NavigateFirefox">NavigateFirefox Overload</a><br /><a href="N_DevCase_ThirdParty_Ndde">DevCase.ThirdParty.Ndde Namespace</a><br />