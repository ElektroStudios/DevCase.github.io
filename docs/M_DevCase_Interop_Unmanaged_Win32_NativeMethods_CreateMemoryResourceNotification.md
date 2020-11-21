# NativeMethods.CreateMemoryResourceNotification Method 
 

Creates a memory resource notification object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static IntPtr CreateMemoryResourceNotification(
	MemoryResourceNotificationType notificationType
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function CreateMemoryResourceNotification ( 
	notificationType As MemoryResourceNotificationType
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim notificationType As MemoryResourceNotificationType
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateMemoryResourceNotification(notificationType)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static IntPtr CreateMemoryResourceNotification(
	MemoryResourceNotificationType notificationType
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member CreateMemoryResourceNotification : 
        notificationType : MemoryResourceNotificationType -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>notificationType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryResourceNotificationType">DevCase.Interop.Unmanaged.Win32.Enums.MemoryResourceNotificationType</a><br />The memory condition under which the object is to be signaled.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to a memory resource notification object. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-creatememoryresourcenotification" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-creatememoryresourcenotification</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />