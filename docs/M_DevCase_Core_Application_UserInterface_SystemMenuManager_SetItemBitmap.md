# SystemMenuManager.SetItemBitmap Method (MenuItem, Bitmap)
 

Set a custom Bitmap image for a menu item.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual bool SetItemBitmap(
	MenuItem item,
	Bitmap bmp
)
```

**VB**<br />
``` VB
Public Overridable Function SetItemBitmap ( 
	item As MenuItem,
	bmp As Bitmap
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim item As MenuItem
Dim bmp As Bitmap
Dim returnValue As Boolean

returnValue = instance.SetItemBitmap(item, 
	bmp)
```

**C++**<br />
``` C++
public:
virtual bool SetItemBitmap(
	MenuItem item, 
	Bitmap^ bmp
)
```

**F#**<br />
``` F#
abstract SetItemBitmap : 
        item : MenuItem * 
        bmp : Bitmap -> bool 
override SetItemBitmap : 
        item : MenuItem * 
        bmp : Bitmap -> bool 
```


#### Parameters
&nbsp;<dl><dt>item</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItem">DevCase.Interop.Unmanaged.Win32.Enums.MenuItem</a><br />The menu item.</dd><dt>bmp</dt><dd>Type: System.Drawing.Bitmap<br />\[Missing <param name="bmp"/> documentation for "M:DevCase.Core.Application.UserInterface.SystemMenuManager.SetItemBitmap(DevCase.Interop.Unmanaged.Win32.Enums.MenuItem,System.Drawing.Bitmap)"\]</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_SystemMenuManager_SetItemBitmap">SetItemBitmap Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />