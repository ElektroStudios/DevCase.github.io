# ProcessInformation.ProcessId Field
 

A value that can be used to identify a process. The value is valid from the time the process is created until all handles to the process are closed and the process object is freed; at this point, the identifier may be reused.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int ProcessId
```

**VB**<br />
``` VB
Public ProcessId As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessInformation
Dim value As Integer

value = instance.ProcessId

instance.ProcessId = value
```

**C++**<br />
``` C++
public:
int ProcessId
```

**F#**<br />
``` F#
val mutable ProcessId: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessInformation">ProcessInformation Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />