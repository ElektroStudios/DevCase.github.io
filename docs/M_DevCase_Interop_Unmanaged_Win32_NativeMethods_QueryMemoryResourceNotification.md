# NativeMethods.QueryMemoryResourceNotification Method 
 

Retrieves the state of the specified memory resource object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool QueryMemoryResourceNotification(
	IntPtr handle,
	out bool refResourceState
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function QueryMemoryResourceNotification ( 
	handle As IntPtr,
	<OutAttribute> ByRef refResourceState As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim handle As IntPtr
Dim refResourceState As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.QueryMemoryResourceNotification(handle, 
	refResourceState)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool QueryMemoryResourceNotification(
	[InAttribute] IntPtr handle, 
	[OutAttribute] bool% refResourceState
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member QueryMemoryResourceNotification : 
        handle : IntPtr * 
        refResourceState : bool byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: System.IntPtr<br />A handle to a memory resource notification object. The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateMemoryResourceNotification">CreateMemoryResourceNotification(MemoryResourceNotificationType)</a> function returns this handle.</dd><dt>refResourceState</dt><dd>Type: System.Boolean<br />The memory pointed to by this parameter receives the state of the memory resource notification object. 

 The value of this parameter is set to `true` (`True` in Visual Basic) if the specified memory condition exists, and `false` (`False` in Visual Basic) if the specified memory condition does not exist.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-querymemoryresourcenotification" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-querymemoryresourcenotification</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />