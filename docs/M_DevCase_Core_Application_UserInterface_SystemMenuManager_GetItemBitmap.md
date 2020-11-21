# SystemMenuManager.GetItemBitmap Method (MenuItem)
 

Returns the custom Bitmap image used by a menu item.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual Bitmap GetItemBitmap(
	MenuItem item
)
```

**VB**<br />
``` VB
Public Overridable Function GetItemBitmap ( 
	item As MenuItem
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim item As MenuItem
Dim returnValue As Bitmap

returnValue = instance.GetItemBitmap(item)
```

**C++**<br />
``` C++
public:
virtual Bitmap^ GetItemBitmap(
	MenuItem item
)
```

**F#**<br />
``` F#
abstract GetItemBitmap : 
        item : MenuItem -> Bitmap 
override GetItemBitmap : 
        item : MenuItem -> Bitmap 
```


#### Parameters
&nbsp;<dl><dt>item</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItem">DevCase.Interop.Unmanaged.Win32.Enums.MenuItem</a><br />The menu item.</dd></dl>

#### Return Value
Type: Bitmap<br />The Bitmap.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_SystemMenuManager_GetItemBitmap">GetItemBitmap Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />