# NativeMethods.EnumProcesses Method 
 

Retrieves the process identifier for each process object in the system.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("PsApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool EnumProcesses(
	uint[] idProcess,
	uint cb,
	out uint refNeeded
)
```

**VB**<br />
``` VB
<DllImportAttribute("PsApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function EnumProcesses ( 
	<OutAttribute> idProcess As UInteger(),
	cb As UInteger,
	<OutAttribute> ByRef refNeeded As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim idProcess As UInteger()
Dim cb As UInteger
Dim refNeeded As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.EnumProcesses(idProcess, 
	cb, refNeeded)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"PsApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool EnumProcesses(
	[InAttribute] [OutAttribute] array<unsigned int>^ idProcess, 
	unsigned int cb, 
	[OutAttribute] unsigned int% refNeeded
)
```

**F#**<br />
``` F#
[<DllImportAttribute("PsApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member EnumProcesses : 
        idProcess : uint32[] byref * 
        cb : uint32 * 
        refNeeded : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>idProcess</dt><dd>Type: System.UInt32[]<br />A pointer to an array that receives the list of process identifiers.</dd><dt>cb</dt><dd>Type: System.UInt32<br />The size of the pProcessIds array, in bytes.</dd><dt>refNeeded</dt><dd>Type: System.UInt32<br />The number of bytes returned in the pProcessIds array.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-enumprocesses" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-enumprocesses</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />