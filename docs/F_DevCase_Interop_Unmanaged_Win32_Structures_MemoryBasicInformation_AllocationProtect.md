# MemoryBasicInformation.AllocationProtect Field
 

The memory protection option when the region was initially allocated. 

 This member can be one of the memory protection constants or 0 if the caller does not have access.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MemoryProtectionOptions AllocationProtect
```

**VB**<br />
``` VB
Public AllocationProtect As MemoryProtectionOptions
```

**VB Usage**<br />
``` VB Usage
Dim instance As MemoryBasicInformation
Dim value As MemoryProtectionOptions

value = instance.AllocationProtect

instance.AllocationProtect = value
```

**C++**<br />
``` C++
public:
MemoryProtectionOptions AllocationProtect
```

**F#**<br />
``` F#
val mutable AllocationProtect: MemoryProtectionOptions
```


#### Field Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">MemoryProtectionOptions</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation">MemoryBasicInformation Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />