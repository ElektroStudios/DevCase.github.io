# DebugUtil.IsWPERunning Method 
 

Determines whether `WPE Pro` (`Winsock Packet Editor`) program is running on the current machine. 

`WPE Pro` is a network protocol analyzer for Windows operating system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsWPERunning()
```

**VB**<br />
``` VB
Public Shared Function IsWPERunning As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = DebugUtil.IsWPERunning()
```

**C++**<br />
``` C++
public:
static bool IsWPERunning()
```

**F#**<br />
``` F#
static member IsWPERunning : unit -> bool 

```


#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if `WPE Pro` program is running on the current machine; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />