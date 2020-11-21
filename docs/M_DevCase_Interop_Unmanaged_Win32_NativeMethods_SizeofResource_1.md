# NativeMethods.SizeofResource Method (IntPtr, IntPtr)
 

Retrieves the size, in bytes, of the specified resource..

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static uint SizeofResource(
	IntPtr hModule,
	IntPtr hResInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function SizeofResource ( 
	hModule As IntPtr,
	hResInfo As IntPtr
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hModule As IntPtr
Dim hResInfo As IntPtr
Dim returnValue As UInteger

returnValue = NativeMethods.SizeofResource(hModule, 
	hResInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static unsigned int SizeofResource(
	IntPtr hModule, 
	IntPtr hResInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member SizeofResource : 
        hModule : IntPtr * 
        hResInfo : IntPtr -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hModule</dt><dd>Type: System.IntPtr<br />A handle to the module whose executable file contains the resource.</dd><dt>hResInfo</dt><dd>Type: System.IntPtr<br />A handle to the resource. This handle must be created by using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FindResource">FindResource(SafeModuleHandle, IntPtr, ResourceType)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FindResourceEx">FindResourceEx(SafeModuleHandle, ResourceType, IntPtr, UInt16)</a> function.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the number of bytes in the resource. 

 If the function fails, the return value is zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms648048%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms648048%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SizeofResource">SizeofResource Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />