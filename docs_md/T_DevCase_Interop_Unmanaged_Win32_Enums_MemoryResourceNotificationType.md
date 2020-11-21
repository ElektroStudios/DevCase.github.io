# MemoryResourceNotificationType Enumeration
 

indicates the memory condition under which an object is to be signaled when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateMemoryResourceNotification">CreateMemoryResourceNotification(MemoryResourceNotificationType)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum MemoryResourceNotificationType
```

**VB**<br />
``` VB
Public Enumeration MemoryResourceNotificationType
```

**VB Usage**<br />
``` VB Usage
Dim instance As MemoryResourceNotificationType
```

**C++**<br />
``` C++
public enum class MemoryResourceNotificationType
```

**F#**<br />
``` F#
type MemoryResourceNotificationType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryResourceNotificationType.LowMemory">**LowMemory**</td><td>0</td><td>Available physical memory is running low.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MemoryResourceNotificationType.HighMemory">**HighMemory**</td><td>1</td><td>Available physical memory is high.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-creatememoryresourcenotification" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-creatememoryresourcenotification</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />