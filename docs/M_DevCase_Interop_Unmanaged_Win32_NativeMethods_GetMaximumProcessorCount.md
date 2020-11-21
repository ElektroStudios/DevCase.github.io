# NativeMethods.GetMaximumProcessorCount Method 
 

Returns the maximum number of logical processors that a processor group or the system can have.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static uint GetMaximumProcessorCount(
	ushort groupNumber
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetMaximumProcessorCount ( 
	groupNumber As UShort
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim groupNumber As UShort
Dim returnValue As UInteger

returnValue = NativeMethods.GetMaximumProcessorCount(groupNumber)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static unsigned int GetMaximumProcessorCount(
	unsigned short groupNumber
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetMaximumProcessorCount : 
        groupNumber : uint16 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>groupNumber</dt><dd>Type: System.UInt16<br />The processor group number. 

 If this parameter is ALL_PROCESSOR_GROUPS, the function returns the maximum number of processors that the system can have.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the maximum number of processors that the specified group can have. 

 If the function fails, the return value is zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getmaximumprocessorcount" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getmaximumprocessorcount</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />