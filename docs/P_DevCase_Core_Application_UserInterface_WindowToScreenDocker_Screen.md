# WindowToScreenDocker.Screen Property 
 

Gets or sets the target Screen where the docking will be performed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual Screen Screen { get; set; }
```

**VB**<br />
``` VB
Public Overridable Property Screen As Screen
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowToScreenDocker
Dim value As Screen

value = instance.Screen

instance.Screen = value
```

**C++**<br />
``` C++
public:
virtual property Screen^ Screen {
	Screen^ get ();
	void set (Screen^ value);
}
```

**F#**<br />
``` F#
abstract Screen : Screen with get, set
override Screen : Screen with get, set
```


#### Property Value
Type: Screen<br />The target Screen where the docking will be performed.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_WindowToScreenDocker">WindowToScreenDocker Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />