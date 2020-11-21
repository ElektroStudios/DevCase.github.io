# MiniDumpExceptionInformation.ClientPointers Field
 

Determines where to get the memory regions pointed to by the ExceptionPointers member. Set to `true` (`True` in Visual Basic) if the memory resides in the process being debugged (the target process of the debugger). Otherwise, set to `false` (`False` in Visual Basic) if the memory resides in the address space of the calling program (the debugger process). 

 If you are accessing local memory (in the calling process) you should not set this member to `true` (`True` in Visual Basic).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool ClientPointers
```

**VB**<br />
``` VB
Public ClientPointers As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As MiniDumpExceptionInformation
Dim value As Boolean

value = instance.ClientPointers

instance.ClientPointers = value
```

**C++**<br />
``` C++
public:
bool ClientPointers
```

**F#**<br />
``` F#
val mutable ClientPointers: bool
```


#### Field Value
Type: Boolean

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MiniDumpExceptionInformation">MiniDumpExceptionInformation Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />