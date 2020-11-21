# SystemMenuManager.RemoveItemBitmap Method (MenuItem)
 

Removes the custom Bitmap image used by a menu item.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual bool RemoveItemBitmap(
	MenuItem item
)
```

**VB**<br />
``` VB
Public Overridable Function RemoveItemBitmap ( 
	item As MenuItem
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim item As MenuItem
Dim returnValue As Boolean

returnValue = instance.RemoveItemBitmap(item)
```

**C++**<br />
``` C++
public:
virtual bool RemoveItemBitmap(
	MenuItem item
)
```

**F#**<br />
``` F#
abstract RemoveItemBitmap : 
        item : MenuItem -> bool 
override RemoveItemBitmap : 
        item : MenuItem -> bool 
```


#### Parameters
&nbsp;<dl><dt>item</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItem">DevCase.Interop.Unmanaged.Win32.Enums.MenuItem</a><br />The menu item.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_SystemMenuManager_RemoveItemBitmap">RemoveItemBitmap Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />