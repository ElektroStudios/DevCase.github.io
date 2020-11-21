# NativeMethods.GetLargePageMinimum Method 
 

Retrieves the minimum size of a large memory page.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static uint GetLargePageMinimum()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function GetLargePageMinimum As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UInteger

returnValue = NativeMethods.GetLargePageMinimum()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static unsigned int GetLargePageMinimum()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member GetLargePageMinimum : unit -> uint32 

```


#### Return Value
Type: UInt32<br />If the processor supports large pages, the return value is the minimum size of a large page. 

 If the processor does not support large pages, the return value is zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-getlargepageminimum" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-getlargepageminimum</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />