# SystemMenuManager.IsMenu Method 
 

Determines whether a handle is a menu handle.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsMenu(
	IntPtr handle
)
```

**VB**<br />
``` VB
Public Shared Function IsMenu ( 
	handle As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim handle As IntPtr
Dim returnValue As Boolean

returnValue = SystemMenuManager.IsMenu(handle)
```

**C++**<br />
``` C++
public:
static bool IsMenu(
	IntPtr handle
)
```

**F#**<br />
``` F#
static member IsMenu : 
        handle : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: System.IntPtr<br />\[Missing <param name="handle"/> documentation for "M:DevCase.Core.Application.UserInterface.SystemMenuManager.IsMenu(System.IntPtr)"\]</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if is a menu handle, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />