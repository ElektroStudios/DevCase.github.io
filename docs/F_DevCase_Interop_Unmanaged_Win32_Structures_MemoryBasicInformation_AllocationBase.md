# MemoryBasicInformation.AllocationBase Field
 

A pointer to the base address of a range of pages allocated by the VirtualAlloc function. 

 The page pointed to by the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_BaseAddress">BaseAddress</a> member is contained within this allocation range.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr AllocationBase
```

**VB**<br />
``` VB
Public AllocationBase As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As MemoryBasicInformation
Dim value As IntPtr

value = instance.AllocationBase

instance.AllocationBase = value
```

**C++**<br />
``` C++
public:
IntPtr AllocationBase
```

**F#**<br />
``` F#
val mutable AllocationBase: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation">MemoryBasicInformation Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />