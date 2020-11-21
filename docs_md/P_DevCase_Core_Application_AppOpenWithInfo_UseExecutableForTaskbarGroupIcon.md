# AppOpenWithInfo.UseExecutableForTaskbarGroupIcon Property 
 

Gets or sets a value indicating whether to use the default icon of this executable in the taskbar if there is no pinnable shortcut for this application, and instead of the icon of the window that was first encountered.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool UseExecutableForTaskbarGroupIcon { get; set; }
```

**VB**<br />
``` VB
Public Property UseExecutableForTaskbarGroupIcon As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppOpenWithInfo
Dim value As Boolean

value = instance.UseExecutableForTaskbarGroupIcon

instance.UseExecutableForTaskbarGroupIcon = value
```

**C++**<br />
``` C++
public:
property bool UseExecutableForTaskbarGroupIcon {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member UseExecutableForTaskbarGroupIcon : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if use the default icon of this executable in the taskbar; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppOpenWithInfo">AppOpenWithInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />