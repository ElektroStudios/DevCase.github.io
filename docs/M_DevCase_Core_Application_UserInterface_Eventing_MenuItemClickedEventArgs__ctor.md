# MenuItemClickedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_UserInterface_Eventing_MenuItemClickedEventArgs">MenuItemClickedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Eventing">DevCase.Core.Application.UserInterface.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MenuItemClickedEventArgs(
	int id,
	string text,
	MenuItemType type,
	MenuItemState state
)
```

**VB**<br />
``` VB
Public Sub New ( 
	id As Integer,
	text As String,
	type As MenuItemType,
	state As MenuItemState
)
```

**VB Usage**<br />
``` VB Usage
Dim id As Integer
Dim text As String
Dim type As MenuItemType
Dim state As MenuItemState

Dim instance As New MenuItemClickedEventArgs(id, text, 
	type, state)
```

**C++**<br />
``` C++
public:
MenuItemClickedEventArgs(
	int id, 
	String^ text, 
	MenuItemType type, 
	MenuItemState state
)
```

**F#**<br />
``` F#
new : 
        id : int * 
        text : string * 
        type : MenuItemType * 
        state : MenuItemState -> MenuItemClickedEventArgs
```


#### Parameters
&nbsp;<dl><dt>id</dt><dd>Type: System.Int32<br />The item identifier.</dd><dt>text</dt><dd>Type: System.String<br />The item text.</dd><dt>type</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemType">DevCase.Interop.Unmanaged.Win32.Enums.MenuItemType</a><br />The item type.</dd><dt>state</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemState">DevCase.Interop.Unmanaged.Win32.Enums.MenuItemState</a><br />The item state.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Eventing_MenuItemClickedEventArgs">MenuItemClickedEventArgs Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Eventing">DevCase.Core.Application.UserInterface.Eventing Namespace</a><br />