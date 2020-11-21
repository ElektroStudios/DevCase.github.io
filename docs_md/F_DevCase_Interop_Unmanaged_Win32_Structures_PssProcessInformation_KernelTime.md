# PssProcessInformation.KernelTime Field
 

The amount of time the process spent executing in kernel-mode.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FILETIME KernelTime
```

**VB**<br />
``` VB
Public KernelTime As FILETIME
```

**VB Usage**<br />
``` VB Usage
Dim instance As PssProcessInformation
Dim value As FILETIME

value = instance.KernelTime

instance.KernelTime = value
```

**C++**<br />
``` C++
public:
FILETIME KernelTime
```

**F#**<br />
``` F#
val mutable KernelTime: FILETIME
```


#### Field Value
Type: FILETIME

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation">PssProcessInformation Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />