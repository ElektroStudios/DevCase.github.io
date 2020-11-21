# SystemMenuManager.SetItemText Method (MenuItem, String)
 

Set the text of a menu item.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual bool SetItemText(
	MenuItem item,
	string text
)
```

**VB**<br />
``` VB
Public Overridable Function SetItemText ( 
	item As MenuItem,
	text As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim item As MenuItem
Dim text As String
Dim returnValue As Boolean

returnValue = instance.SetItemText(item, 
	text)
```

**C++**<br />
``` C++
public:
virtual bool SetItemText(
	MenuItem item, 
	String^ text
)
```

**F#**<br />
``` F#
abstract SetItemText : 
        item : MenuItem * 
        text : string -> bool 
override SetItemText : 
        item : MenuItem * 
        text : string -> bool 
```


#### Parameters
&nbsp;<dl><dt>item</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItem">DevCase.Interop.Unmanaged.Win32.Enums.MenuItem</a><br />The menu item.</dd><dt>text</dt><dd>Type: System.String<br />The new text for the item.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_SystemMenuManager_SetItemText">SetItemText Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />