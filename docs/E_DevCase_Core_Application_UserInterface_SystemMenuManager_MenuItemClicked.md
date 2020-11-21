# SystemMenuManager.MenuItemClicked Event
 

Occurs when a menu item is clicked.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MenuItemClickedEventArgs> MenuItemClicked
```

**VB**<br />
``` VB
Public Event MenuItemClicked As EventHandler(Of MenuItemClickedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim handler As EventHandler(Of MenuItemClickedEventArgs)

AddHandler instance.MenuItemClicked, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MenuItemClickedEventArgs^>^ MenuItemClicked {
	void add (EventHandler<MenuItemClickedEventArgs^>^ value);
	void remove (EventHandler<MenuItemClickedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member MenuItemClicked : IEvent<EventHandler<MenuItemClickedEventArgs>,
    MenuItemClickedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_Application_UserInterface_Eventing_MenuItemClickedEventArgs">MenuItemClickedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />