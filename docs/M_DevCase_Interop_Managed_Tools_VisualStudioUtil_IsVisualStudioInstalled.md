# VisualStudioUtil.IsVisualStudioInstalled Method 
 

Determines whether at least one version of Visual Studio is installed in the current machine.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsVisualStudioInstalled()
```

**VB**<br />
``` VB
Public Shared Function IsVisualStudioInstalled As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = VisualStudioUtil.IsVisualStudioInstalled()
```

**C++**<br />
``` C++
public:
static bool IsVisualStudioInstalled()
```

**F#**<br />
``` F#
static member IsVisualStudioInstalled : unit -> bool 

```


#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if at least one version of Visual Studio is installed in the current machine; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isVisualStudioInstalled As Boolean = IsVisualStudioInstalled()
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_VisualStudioUtil">VisualStudioUtil Class</a><br /><a href="Overload_DevCase_Interop_Managed_Tools_VisualStudioUtil_IsVisualStudioInstalled">IsVisualStudioInstalled Overload</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />