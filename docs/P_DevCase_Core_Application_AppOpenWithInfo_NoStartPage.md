# AppOpenWithInfo.NoStartPage Property 
 

Gets or sets a value indicating whether the application executable and shortcuts should be excluded from the Start menu and from pinning or inclusion in the MFU list. 

 This entry is typically used to exclude system tools, installers and uninstallers, and readme files.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool NoStartPage { get; set; }
```

**VB**<br />
``` VB
Public Property NoStartPage As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppOpenWithInfo
Dim value As Boolean

value = instance.NoStartPage

instance.NoStartPage = value
```

**C++**<br />
``` C++
public:
property bool NoStartPage {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member NoStartPage : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the application executable and shortcuts should be excluded from the Start menu and from pinning or inclusion in the MFU list; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppOpenWithInfo">AppOpenWithInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />