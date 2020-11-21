# NativeMethods.GetMaximumProcessorGroupCount Method 
 

Returns the maximum number of processor groups that the system can have.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static ushort GetMaximumProcessorGroupCount()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function GetMaximumProcessorGroupCount As UShort
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UShort

returnValue = NativeMethods.GetMaximumProcessorGroupCount()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static unsigned short GetMaximumProcessorGroupCount()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member GetMaximumProcessorGroupCount : unit -> uint16 

```


#### Return Value
Type: UInt16<br />If the function succeeds, the return value is the maximum number of processor groups that the system can have. 

 If the function fails, the return value is zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getmaximumprocessorgroupcount" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getmaximumprocessorgroupcount</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />