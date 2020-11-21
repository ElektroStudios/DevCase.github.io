# SystemMenuManager.AddItem Method 
 

Adds an Item at the given position.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual bool AddItem(
	string label,
	int id,
	int position,
	Bitmap imageChecked = null,
	Bitmap imageUnchecked = null
)
```

**VB**<br />
``` VB
Public Overridable Function AddItem ( 
	label As String,
	id As Integer,
	position As Integer,
	Optional imageChecked As Bitmap = Nothing,
	Optional imageUnchecked As Bitmap = Nothing
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim label As String
Dim id As Integer
Dim position As Integer
Dim imageChecked As Bitmap
Dim imageUnchecked As Bitmap
Dim returnValue As Boolean

returnValue = instance.AddItem(label, 
	id, position, imageChecked, imageUnchecked)
```

**C++**<br />
``` C++
public:
virtual bool AddItem(
	String^ label, 
	int id, 
	int position, 
	Bitmap^ imageChecked = nullptr, 
	Bitmap^ imageUnchecked = nullptr
)
```

**F#**<br />
``` F#
abstract AddItem : 
        label : string * 
        id : int * 
        position : int * 
        ?imageChecked : Bitmap * 
        ?imageUnchecked : Bitmap 
(* Defaults:
        let _imageChecked = defaultArg imageChecked null
        let _imageUnchecked = defaultArg imageUnchecked null
*)
-> bool 
override AddItem : 
        label : string * 
        id : int * 
        position : int * 
        ?imageChecked : Bitmap * 
        ?imageUnchecked : Bitmap 
(* Defaults:
        let _imageChecked = defaultArg imageChecked null
        let _imageUnchecked = defaultArg imageUnchecked null
*)
-> bool 
```


#### Parameters
&nbsp;<dl><dt>label</dt><dd>Type: System.String<br />The text of the item.</dd><dt>id</dt><dd>Type: System.Int32<br />A Identifier to interact with this item when is clicked.</dd><dt>position</dt><dd>Type: System.Int32<br />The position where the item will be added.</dd><dt>imageChecked (Optional)</dt><dd>Type: System.Drawing.Bitmap<br />Image displayed when Item is selected.</dd><dt>imageUnchecked (Optional)</dt><dd>Type: System.Drawing.Bitmap<br />Image displayed when Item is not selected.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />