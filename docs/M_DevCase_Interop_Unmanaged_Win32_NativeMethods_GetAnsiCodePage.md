# NativeMethods.GetAnsiCodePage Method 
 

Retrieves the current Windows ANSI code page identifier for the operating system.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", EntryPoint = "GetACP", ExactSpelling = true)]
public static uint GetAnsiCodePage()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", EntryPoint := "GetACP", ExactSpelling := true>]
Public Shared Function GetAnsiCodePage As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UInteger

returnValue = NativeMethods.GetAnsiCodePage()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", EntryPoint = L"GetACP", ExactSpelling = true)]
static unsigned int GetAnsiCodePage()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", EntryPoint = "GetACP", ExactSpelling = true)>]
static member GetAnsiCodePage : unit -> uint32 

```


#### Return Value
Type: UInt32<br />Returns the current Windows ANSI code page (ACP) identifier for the operating system.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getacp" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getacp</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />