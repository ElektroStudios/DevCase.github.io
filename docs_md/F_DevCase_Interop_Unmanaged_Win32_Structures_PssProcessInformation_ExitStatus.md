# PssProcessInformation.ExitStatus Field
 

The exit code of the process. If the process has not exited, this is set to `STILL_ACTIVE` (259).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public uint ExitStatus
```

**VB**<br />
``` VB
Public ExitStatus As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim instance As PssProcessInformation
Dim value As UInteger

value = instance.ExitStatus

instance.ExitStatus = value
```

**C++**<br />
``` C++
public:
unsigned int ExitStatus
```

**F#**<br />
``` F#
val mutable ExitStatus: uint32
```


#### Field Value
Type: UInt32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation">PssProcessInformation Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />