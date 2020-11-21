# SystemMenuManager.RemoveItemBitmap Method (Int32)
 

Removes the custom Bitmap image used by a menu item at given position.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual bool RemoveItemBitmap(
	int position
)
```

**VB**<br />
``` VB
Public Overridable Function RemoveItemBitmap ( 
	position As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim position As Integer
Dim returnValue As Boolean

returnValue = instance.RemoveItemBitmap(position)
```

**C++**<br />
``` C++
public:
virtual bool RemoveItemBitmap(
	int position
)
```

**F#**<br />
``` F#
abstract RemoveItemBitmap : 
        position : int -> bool 
override RemoveItemBitmap : 
        position : int -> bool 
```


#### Parameters
&nbsp;<dl><dt>position</dt><dd>Type: System.Int32<br />The menu item position.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_SystemMenuManager_RemoveItemBitmap">RemoveItemBitmap Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />