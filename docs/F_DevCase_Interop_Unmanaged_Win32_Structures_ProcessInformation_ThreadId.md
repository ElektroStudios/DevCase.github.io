# ProcessInformation.ThreadId Field
 

A value that can be used to identify a thread. The value is valid from the time the thread is created until all handles to the thread are closed and the thread object is freed; at this point, the identifier may be reused.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int ThreadId
```

**VB**<br />
``` VB
Public ThreadId As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessInformation
Dim value As Integer

value = instance.ThreadId

instance.ThreadId = value
```

**C++**<br />
``` C++
public:
int ThreadId
```

**F#**<br />
``` F#
val mutable ThreadId: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessInformation">ProcessInformation Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />