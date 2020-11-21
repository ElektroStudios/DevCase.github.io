# UndoRedoItem.CurrentValue Property 
 

Gets or sets the current value on the control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Object CurrentValue { get; set; }
```

**VB**<br />
``` VB
Public Property CurrentValue As Object
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As UndoRedoItem
Dim value As Object

value = instance.CurrentValue

instance.CurrentValue = value
```

**C++**<br />
``` C++
public:
property Object^ CurrentValue {
	Object^ get ();
	void set (Object^ value);
}
```

**F#**<br />
``` F#
member CurrentValue : Object with get, set

```


#### Property Value
Type: Object<br />The current value on the control.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_UndoRedoItem">UndoRedoItem Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />