# SystemMenuManager.SetItemBitmap Method (Int32, Bitmap)
 

Set a custom Bitmap image for a menu item at given position.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual bool SetItemBitmap(
	int position,
	Bitmap bmp
)
```

**VB**<br />
``` VB
Public Overridable Function SetItemBitmap ( 
	position As Integer,
	bmp As Bitmap
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim position As Integer
Dim bmp As Bitmap
Dim returnValue As Boolean

returnValue = instance.SetItemBitmap(position, 
	bmp)
```

**C++**<br />
``` C++
public:
virtual bool SetItemBitmap(
	int position, 
	Bitmap^ bmp
)
```

**F#**<br />
``` F#
abstract SetItemBitmap : 
        position : int * 
        bmp : Bitmap -> bool 
override SetItemBitmap : 
        position : int * 
        bmp : Bitmap -> bool 
```


#### Parameters
&nbsp;<dl><dt>position</dt><dd>Type: System.Int32<br />The menu item position.</dd><dt>bmp</dt><dd>Type: System.Drawing.Bitmap<br />\[Missing <param name="bmp"/> documentation for "M:DevCase.Core.Application.UserInterface.SystemMenuManager.SetItemBitmap(System.Int32,System.Drawing.Bitmap)"\]</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_SystemMenuManager_SetItemBitmap">SetItemBitmap Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />