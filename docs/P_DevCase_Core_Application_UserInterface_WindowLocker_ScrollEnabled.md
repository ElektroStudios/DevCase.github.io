# WindowLocker.ScrollEnabled Property 
 

Gets or sets a value indicating whether the horizontal and vertical scrolling of the window is enabled.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual bool ScrollEnabled { get; set; }
```

**VB**<br />
``` VB
Public Overridable Property ScrollEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowLocker
Dim value As Boolean

value = instance.ScrollEnabled

instance.ScrollEnabled = value
```

**C++**<br />
``` C++
public:
virtual property bool ScrollEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
abstract ScrollEnabled : bool with get, set
override ScrollEnabled : bool with get, set
```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the horizontal and vertical scrolling is enabled; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_WindowLocker">WindowLocker Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />