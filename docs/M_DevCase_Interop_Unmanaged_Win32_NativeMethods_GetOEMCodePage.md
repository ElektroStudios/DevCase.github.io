# NativeMethods.GetOEMCodePage Method 
 

Returns the current original equipment manufacturer (OEM) code page identifier for the operating system. 

 Note: The ANSI code pages can be different on different computers, or can be changed for a single computer, leading to data corruption. 

 For the most consistent results, applications should use Unicode, such as UTF-8 or UTF-16, instead of a specific code page.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", EntryPoint = "GetOEMCP", ExactSpelling = true)]
public static uint GetOEMCodePage()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", EntryPoint := "GetOEMCP", ExactSpelling := true>]
Public Shared Function GetOEMCodePage As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UInteger

returnValue = NativeMethods.GetOEMCodePage()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", EntryPoint = L"GetOEMCP", ExactSpelling = true)]
static unsigned int GetOEMCodePage()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", EntryPoint = "GetOEMCP", ExactSpelling = true)>]
static member GetOEMCodePage : unit -> uint32 

```


#### Return Value
Type: UInt32<br />Returns the current OEM code page identifier for the operating system.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getoemcp" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getoemcp</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />