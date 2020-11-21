# DebugUtil.IsWiresharkRunning Method 
 

Determines whether `Wireshark` program is running on the current machine. 

`Wireshark` is a network protocol analyzer for Windows operating system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsWiresharkRunning()
```

**VB**<br />
``` VB
Public Shared Function IsWiresharkRunning As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = DebugUtil.IsWiresharkRunning()
```

**C++**<br />
``` C++
public:
static bool IsWiresharkRunning()
```

**F#**<br />
``` F#
static member IsWiresharkRunning : unit -> bool 

```


#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if `Wireshark` program is running on the current machine; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="http://www.wireshark.org/" target="_blank">http://www.wireshark.org/</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />