# ProcessInformation.hThread Field
 

A handle to the primary thread of the newly created process. The handle is used to specify the thread in all functions that perform operations on the thread object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr hThread
```

**VB**<br />
``` VB
Public hThread As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessInformation
Dim value As IntPtr

value = instance.hThread

instance.hThread = value
```

**C++**<br />
``` C++
public:
IntPtr hThread
```

**F#**<br />
``` F#
val mutable hThread: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessInformation">ProcessInformation Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />