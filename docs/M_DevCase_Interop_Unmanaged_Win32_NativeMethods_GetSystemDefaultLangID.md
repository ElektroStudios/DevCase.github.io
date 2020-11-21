# NativeMethods.GetSystemDefaultLangID Method 
 

Returns the language identifier for the system locale.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static ushort GetSystemDefaultLangID()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function GetSystemDefaultLangID As UShort
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UShort

returnValue = NativeMethods.GetSystemDefaultLangID()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static unsigned short GetSystemDefaultLangID()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member GetSystemDefaultLangID : unit -> uint16 

```


#### Return Value
Type: UInt16<br />Returns the language identifier for the system locale. This is the language used when displaying text in programs that do not support Unicode.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getsystemdefaultlangid" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getsystemdefaultlangid</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />