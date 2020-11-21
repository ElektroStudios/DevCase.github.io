# EditControlHook.Controls Property 
 

Gets or sets the edit-controls that will notify for windows messages.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Control[] Controls { get; set; }
```

**VB**<br />
``` VB
Public Property Controls As Control()
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As EditControlHook
Dim value As Control()

value = instance.Controls

instance.Controls = value
```

**C++**<br />
``` C++
public:
property array<Control^>^ Controls {
	array<Control^>^ get ();
	void set (array<Control^>^ value);
}
```

**F#**<br />
``` F#
member Controls : Control[] with get, set

```


#### Property Value
Type: Control[]<br />The controls.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_EditControlHook">EditControlHook Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />