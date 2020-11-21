# NativeMethods.GetSystemDpiForProcess Method 
 

Retrieves the system DPI associated with a given process. 

 This is useful for avoiding compatibility issues that arise from sharing DPI-sensitive information between multiple system-aware processes with different system DPI values.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static uint GetSystemDpiForProcess(
	IntPtr hProcess
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetSystemDpiForProcess ( 
	hProcess As IntPtr
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim returnValue As UInteger

returnValue = NativeMethods.GetSystemDpiForProcess(hProcess)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static unsigned int GetSystemDpiForProcess(
	IntPtr hProcess
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetSystemDpiForProcess : 
        hProcess : IntPtr -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />The handle for the process to examine. 

 If this value is Zero, this API behaves identically to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetDpiForSystem">GetDpiForSystem()</a>.</dd></dl>

#### Return Value
Type: UInt32<br />The process's system DPI value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getsystemdpiforprocess" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getsystemdpiforprocess</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />