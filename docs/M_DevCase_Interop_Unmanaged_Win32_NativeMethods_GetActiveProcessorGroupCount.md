# NativeMethods.GetActiveProcessorGroupCount Method 
 

Returns the number of active processor groups in the system.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static ushort GetActiveProcessorGroupCount()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function GetActiveProcessorGroupCount As UShort
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UShort

returnValue = NativeMethods.GetActiveProcessorGroupCount()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static unsigned short GetActiveProcessorGroupCount()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member GetActiveProcessorGroupCount : unit -> uint16 

```


#### Return Value
Type: UInt16<br />If the function succeeds, the return value is the number of active processor groups in the system. 

 If the function fails, the return value is zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getactiveprocessorgroupcount" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getactiveprocessorgroupcount</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />