# SystemMenuManager.GetItemText Method (MenuItem)
 

Gets the text of a menu item.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual string GetItemText(
	MenuItem item
)
```

**VB**<br />
``` VB
Public Overridable Function GetItemText ( 
	item As MenuItem
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim item As MenuItem
Dim returnValue As String

returnValue = instance.GetItemText(item)
```

**C++**<br />
``` C++
public:
virtual String^ GetItemText(
	MenuItem item
)
```

**F#**<br />
``` F#
abstract GetItemText : 
        item : MenuItem -> string 
override GetItemText : 
        item : MenuItem -> string 
```


#### Parameters
&nbsp;<dl><dt>item</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItem">DevCase.Interop.Unmanaged.Win32.Enums.MenuItem</a><br />\[Missing <param name="item"/> documentation for "M:DevCase.Core.Application.UserInterface.SystemMenuManager.GetItemText(DevCase.Interop.Unmanaged.Win32.Enums.MenuItem)"\]</dd></dl>

#### Return Value
Type: String<br />The item text.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_SystemMenuManager_GetItemText">GetItemText Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />