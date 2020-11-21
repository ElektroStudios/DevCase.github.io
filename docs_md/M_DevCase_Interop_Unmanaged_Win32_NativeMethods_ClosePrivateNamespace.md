# NativeMethods.ClosePrivateNamespace Method 
 

Closes an open namespace handle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool ClosePrivateNamespace(
	IntPtr handle,
	uint flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function ClosePrivateNamespace ( 
	handle As IntPtr,
	flags As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim handle As IntPtr
Dim flags As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.ClosePrivateNamespace(handle, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool ClosePrivateNamespace(
	[InAttribute] IntPtr handle, 
	[InAttribute] unsigned int flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member ClosePrivateNamespace : 
        handle : IntPtr * 
        flags : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: System.IntPtr<br />The namespace handle. This handle is created by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreatePrivateNamespace">CreatePrivateNamespace(SecurityAttributes, IntPtr, String)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenPrivateNamespace">OpenPrivateNamespace(IntPtr, String)</a>.</dd><dt>flags</dt><dd>Type: System.UInt32<br />If this parameter is PRIVATE_NAMESPACE_FLAG_DESTROY (0x00000001), the namespace is destroyed.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms682026(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms682026(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />