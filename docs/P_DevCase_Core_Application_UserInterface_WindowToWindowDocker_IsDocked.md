# WindowToWindowDocker.IsDocked Property 
 

Gets a value indicating whether the owner window is docked.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual bool IsDocked { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property IsDocked As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowToWindowDocker
Dim value As Boolean

value = instance.IsDocked

```

**C++**<br />
``` C++
public:
virtual property bool IsDocked {
	bool get ();
}
```

**F#**<br />
``` F#
abstract IsDocked : bool with get
override IsDocked : bool with get
```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the owner window is docked; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_WindowToWindowDocker">WindowToWindowDocker Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />