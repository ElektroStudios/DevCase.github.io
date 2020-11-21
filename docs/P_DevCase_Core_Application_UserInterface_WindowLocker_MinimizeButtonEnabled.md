# WindowLocker.MinimizeButtonEnabled Property 
 

Gets or sets a value indicating whether the Minimize button of the window is enabled.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual bool MinimizeButtonEnabled { get; set; }
```

**VB**<br />
``` VB
Public Overridable Property MinimizeButtonEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowLocker
Dim value As Boolean

value = instance.MinimizeButtonEnabled

instance.MinimizeButtonEnabled = value
```

**C++**<br />
``` C++
public:
virtual property bool MinimizeButtonEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
abstract MinimizeButtonEnabled : bool with get, set
override MinimizeButtonEnabled : bool with get, set
```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the Minimize button is enabled; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_WindowLocker">WindowLocker Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />