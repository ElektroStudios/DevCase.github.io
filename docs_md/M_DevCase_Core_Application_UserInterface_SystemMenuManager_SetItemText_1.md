# SystemMenuManager.SetItemText Method (Int32, String)
 

Set the text of a menu item at given position.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual bool SetItemText(
	int position,
	string text
)
```

**VB**<br />
``` VB
Public Overridable Function SetItemText ( 
	position As Integer,
	text As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim position As Integer
Dim text As String
Dim returnValue As Boolean

returnValue = instance.SetItemText(position, 
	text)
```

**C++**<br />
``` C++
public:
virtual bool SetItemText(
	int position, 
	String^ text
)
```

**F#**<br />
``` F#
abstract SetItemText : 
        position : int * 
        text : string -> bool 
override SetItemText : 
        position : int * 
        text : string -> bool 
```


#### Parameters
&nbsp;<dl><dt>position</dt><dd>Type: System.Int32<br />The menu item position.</dd><dt>text</dt><dd>Type: System.String<br />The new text for the item.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_SystemMenuManager_SetItemText">SetItemText Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />