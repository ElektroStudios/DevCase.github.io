# SystemMenuManager.GetItemState Method (Int32)
 

Gets the state of a menu item at given position.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual MenuItemState GetItemState(
	int position
)
```

**VB**<br />
``` VB
Public Overridable Function GetItemState ( 
	position As Integer
) As MenuItemState
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim position As Integer
Dim returnValue As MenuItemState

returnValue = instance.GetItemState(position)
```

**C++**<br />
``` C++
public:
virtual MenuItemState GetItemState(
	int position
)
```

**F#**<br />
``` F#
abstract GetItemState : 
        position : int -> MenuItemState 
override GetItemState : 
        position : int -> MenuItemState 
```


#### Parameters
&nbsp;<dl><dt>position</dt><dd>Type: System.Int32<br />\[Missing <param name="position"/> documentation for "M:DevCase.Core.Application.UserInterface.SystemMenuManager.GetItemState(System.Int32)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemState">MenuItemState</a><br />The item state.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_SystemMenuManager_GetItemState">GetItemState Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />