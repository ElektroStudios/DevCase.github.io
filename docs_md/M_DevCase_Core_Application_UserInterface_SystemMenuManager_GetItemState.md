# SystemMenuManager.GetItemState Method (MenuItem)
 

Gets the state of a menu item.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual MenuItemState GetItemState(
	MenuItem item
)
```

**VB**<br />
``` VB
Public Overridable Function GetItemState ( 
	item As MenuItem
) As MenuItemState
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim item As MenuItem
Dim returnValue As MenuItemState

returnValue = instance.GetItemState(item)
```

**C++**<br />
``` C++
public:
virtual MenuItemState GetItemState(
	MenuItem item
)
```

**F#**<br />
``` F#
abstract GetItemState : 
        item : MenuItem -> MenuItemState 
override GetItemState : 
        item : MenuItem -> MenuItemState 
```


#### Parameters
&nbsp;<dl><dt>item</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItem">DevCase.Interop.Unmanaged.Win32.Enums.MenuItem</a><br />\[Missing <param name="item"/> documentation for "M:DevCase.Core.Application.UserInterface.SystemMenuManager.GetItemState(DevCase.Interop.Unmanaged.Win32.Enums.MenuItem)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemState">MenuItemState</a><br />The item state.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_SystemMenuManager_GetItemState">GetItemState Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />