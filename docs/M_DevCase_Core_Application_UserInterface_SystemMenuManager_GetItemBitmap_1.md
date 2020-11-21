# SystemMenuManager.GetItemBitmap Method (Int32)
 

Returns the custom Bitmap image used by a menu item at given position.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual Bitmap GetItemBitmap(
	int position
)
```

**VB**<br />
``` VB
Public Overridable Function GetItemBitmap ( 
	position As Integer
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim position As Integer
Dim returnValue As Bitmap

returnValue = instance.GetItemBitmap(position)
```

**C++**<br />
``` C++
public:
virtual Bitmap^ GetItemBitmap(
	int position
)
```

**F#**<br />
``` F#
abstract GetItemBitmap : 
        position : int -> Bitmap 
override GetItemBitmap : 
        position : int -> Bitmap 
```


#### Parameters
&nbsp;<dl><dt>position</dt><dd>Type: System.Int32<br />The menu item position.</dd></dl>

#### Return Value
Type: Bitmap<br />The Bitmap.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_SystemMenuManager_GetItemBitmap">GetItemBitmap Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />