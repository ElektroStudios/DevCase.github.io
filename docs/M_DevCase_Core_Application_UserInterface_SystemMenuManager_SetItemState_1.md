# SystemMenuManager.SetItemState Method (Int32, MenuItemState)
 

Set an state for a menu item at given position.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual bool SetItemState(
	int position,
	MenuItemState state
)
```

**VB**<br />
``` VB
Public Overridable Function SetItemState ( 
	position As Integer,
	state As MenuItemState
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim position As Integer
Dim state As MenuItemState
Dim returnValue As Boolean

returnValue = instance.SetItemState(position, 
	state)
```

**C++**<br />
``` C++
public:
virtual bool SetItemState(
	int position, 
	MenuItemState state
)
```

**F#**<br />
``` F#
abstract SetItemState : 
        position : int * 
        state : MenuItemState -> bool 
override SetItemState : 
        position : int * 
        state : MenuItemState -> bool 
```


#### Parameters
&nbsp;<dl><dt>position</dt><dd>Type: System.Int32<br />The menu item position.</dd><dt>state</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemState">DevCase.Interop.Unmanaged.Win32.Enums.MenuItemState</a><br />The new state for the item.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_SystemMenuManager_SetItemState">SetItemState Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />