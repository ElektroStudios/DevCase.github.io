# NativeMethods.EnumProcessModulesEx Method 
 

Retrieves a handle for each module in the specified process that meets the specified filter criteria.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("PsApi.dll", ExactSpelling = true, SetLastError = true)]
public static bool EnumProcessModulesEx(
	IntPtr hProcess,
	IntPtr[] module,
	uint cb,
	out uint refNeeded,
	EnumProcessModulesFilter filterFlag
)
```

**VB**<br />
``` VB
<DllImportAttribute("PsApi.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function EnumProcessModulesEx ( 
	hProcess As IntPtr,
	<OutAttribute> module As IntPtr(),
	cb As UInteger,
	<OutAttribute> ByRef refNeeded As UInteger,
	filterFlag As EnumProcessModulesFilter
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim module As IntPtr()
Dim cb As UInteger
Dim refNeeded As UInteger
Dim filterFlag As EnumProcessModulesFilter
Dim returnValue As Boolean

returnValue = NativeMethods.EnumProcessModulesEx(hProcess, 
	module, cb, refNeeded, filterFlag)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"PsApi.dll", ExactSpelling = true, SetLastError = true)]
static bool EnumProcessModulesEx(
	IntPtr hProcess, 
	[InAttribute] [OutAttribute] array<IntPtr>^ module, 
	unsigned int cb, 
	[OutAttribute] unsigned int% refNeeded, 
	EnumProcessModulesFilter filterFlag
)
```

**F#**<br />
``` F#
[<DllImportAttribute("PsApi.dll", ExactSpelling = true, SetLastError = true)>]
static member EnumProcessModulesEx : 
        hProcess : IntPtr * 
        module : IntPtr[] byref * 
        cb : uint32 * 
        refNeeded : uint32 byref * 
        filterFlag : EnumProcessModulesFilter -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process.</dd><dt>module</dt><dd>Type: System.IntPtr[]<br />\[Missing <param name="module"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.EnumProcessModulesEx(System.IntPtr,System.IntPtr[],System.UInt32,System.UInt32@,DevCase.Interop.Unmanaged.Win32.Enums.EnumProcessModulesFilter)"\]</dd><dt>cb</dt><dd>Type: System.UInt32<br />The size of the *[module]* array, in bytes.</dd><dt>refNeeded</dt><dd>Type: System.UInt32<br />The number of bytes required to store all module handles in the *[module]* array.</dd><dt>filterFlag</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EnumProcessModulesFilter">DevCase.Interop.Unmanaged.Win32.Enums.EnumProcessModulesFilter</a><br />The filter criteria.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-enumprocessmodulesex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-enumprocessmodulesex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />