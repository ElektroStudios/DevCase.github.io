# NativeMethods.LoadResource Method (IntPtr, IntPtr)
 

Retrieves a handle that can be used to obtain a pointer to the first byte of the specified resource in memory.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static IntPtr LoadResource(
	IntPtr hModule,
	IntPtr hResInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function LoadResource ( 
	hModule As IntPtr,
	hResInfo As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hModule As IntPtr
Dim hResInfo As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.LoadResource(hModule, 
	hResInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static IntPtr LoadResource(
	IntPtr hModule, 
	IntPtr hResInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member LoadResource : 
        hModule : IntPtr * 
        hResInfo : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hModule</dt><dd>Type: System.IntPtr<br />A handle to the module whose executable file contains the resource. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the system loads the resource from the module that was used to create the current process.</dd><dt>hResInfo</dt><dd>Type: System.IntPtr<br />A handle to the resource to be loaded. This handle is returned by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FindResource">FindResource(SafeModuleHandle, IntPtr, ResourceType)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FindResourceEx">FindResourceEx(SafeModuleHandle, ResourceType, IntPtr, UInt16)</a> function.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the data associated with the resource. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648046%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648046%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadResource">LoadResource Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />