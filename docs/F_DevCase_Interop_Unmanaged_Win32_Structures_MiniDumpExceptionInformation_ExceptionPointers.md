# MiniDumpExceptionInformation.ExceptionPointers Field
 

A pointer to an `EXCEPTION_POINTERS` structure ( GetExceptionPointers() ) specifying a computer-independent description of the exception and the processor context at the time of the exception.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr ExceptionPointers
```

**VB**<br />
``` VB
Public ExceptionPointers As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As MiniDumpExceptionInformation
Dim value As IntPtr

value = instance.ExceptionPointers

instance.ExceptionPointers = value
```

**C++**<br />
``` C++
public:
IntPtr ExceptionPointers
```

**F#**<br />
``` F#
val mutable ExceptionPointers: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MiniDumpExceptionInformation">MiniDumpExceptionInformation Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />