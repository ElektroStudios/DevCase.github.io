# WindowLocker.MaximizeButtonEnabled Property 
 

Gets or sets a value indicating whether the Maximize button of the window is enabled.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual bool MaximizeButtonEnabled { get; set; }
```

**VB**<br />
``` VB
Public Overridable Property MaximizeButtonEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowLocker
Dim value As Boolean

value = instance.MaximizeButtonEnabled

instance.MaximizeButtonEnabled = value
```

**C++**<br />
``` C++
public:
virtual property bool MaximizeButtonEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
abstract MaximizeButtonEnabled : bool with get, set
override MaximizeButtonEnabled : bool with get, set
```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the Close button is enabled; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_WindowLocker">WindowLocker Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />