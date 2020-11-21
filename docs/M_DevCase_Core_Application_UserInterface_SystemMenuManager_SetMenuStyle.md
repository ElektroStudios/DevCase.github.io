# SystemMenuManager.SetMenuStyle Method 
 

Set the menu style.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual bool SetMenuStyle(
	MenuStyle style
)
```

**VB**<br />
``` VB
Public Overridable Function SetMenuStyle ( 
	style As MenuStyle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim style As MenuStyle
Dim returnValue As Boolean

returnValue = instance.SetMenuStyle(style)
```

**C++**<br />
``` C++
public:
virtual bool SetMenuStyle(
	MenuStyle style
)
```

**F#**<br />
``` F#
abstract SetMenuStyle : 
        style : MenuStyle -> bool 
override SetMenuStyle : 
        style : MenuStyle -> bool 
```


#### Parameters
&nbsp;<dl><dt>style</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuStyle">DevCase.Interop.Unmanaged.Win32.Enums.MenuStyle</a><br />\[Missing <param name="style"/> documentation for "M:DevCase.Core.Application.UserInterface.SystemMenuManager.SetMenuStyle(DevCase.Interop.Unmanaged.Win32.Enums.MenuStyle)"\]</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />