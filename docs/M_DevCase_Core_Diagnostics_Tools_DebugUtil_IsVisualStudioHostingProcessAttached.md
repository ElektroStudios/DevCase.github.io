# DebugUtil.IsVisualStudioHostingProcessAttached Method 
 

Determines whether the Visual Studio Hosting Process (vshost.exe) is attached on the current process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsVisualStudioHostingProcessAttached()
```

**VB**<br />
``` VB
Public Shared Function IsVisualStudioHostingProcessAttached As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = DebugUtil.IsVisualStudioHostingProcessAttached()
```

**C++**<br />
``` C++
public:
static bool IsVisualStudioHostingProcessAttached()
```

**F#**<br />
``` F#
static member IsVisualStudioHostingProcessAttached : unit -> bool 

```


#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if Visual Studio Hosting Process (vshost.exe) is attached; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isVshostAttached As Boolean = IsVisualStudioHostingProcessAttached()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />