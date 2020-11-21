# SystemMenuManager.SetMenuBackColor Method 
 

Set the background color of a menu.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual bool SetMenuBackColor(
	Color color
)
```

**VB**<br />
``` VB
Public Overridable Function SetMenuBackColor ( 
	color As Color
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim color As Color
Dim returnValue As Boolean

returnValue = instance.SetMenuBackColor(color)
```

**C++**<br />
``` C++
public:
virtual bool SetMenuBackColor(
	Color color
)
```

**F#**<br />
``` F#
abstract SetMenuBackColor : 
        color : Color -> bool 
override SetMenuBackColor : 
        color : Color -> bool 
```


#### Parameters
&nbsp;<dl><dt>color</dt><dd>Type: System.Drawing.Color<br />\[Missing <param name="color"/> documentation for "M:DevCase.Core.Application.UserInterface.SystemMenuManager.SetMenuBackColor(System.Drawing.Color)"\]</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />