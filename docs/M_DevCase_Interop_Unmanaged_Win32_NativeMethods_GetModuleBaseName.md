# NativeMethods.GetModuleBaseName Method 
 

Retrieves the base name of the specified module.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("PsApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GetModuleBaseName(
	IntPtr hProcess,
	[OptionalAttribute] IntPtr hModule,
	StringBuilder baseName,
	uint size
)
```

**VB**<br />
``` VB
<DllImportAttribute("PsApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetModuleBaseName ( 
	hProcess As IntPtr,
	<OptionalAttribute> hModule As IntPtr,
	baseName As StringBuilder,
	size As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim hModule As IntPtr
Dim baseName As StringBuilder
Dim size As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetModuleBaseName(hProcess, 
	hModule, baseName, size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"PsApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GetModuleBaseName(
	IntPtr hProcess, 
	[OptionalAttribute] IntPtr hModule, 
	StringBuilder^ baseName, 
	unsigned int size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("PsApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetModuleBaseName : 
        hProcess : IntPtr * 
        [<OptionalAttribute>] hModule : IntPtr * 
        baseName : StringBuilder * 
        size : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryLimitedInformation</a> access right.</dd><dt>hModule (Optional)</dt><dd>Type: System.IntPtr<br />A handle to the module. 

 If this parameter is Zero, this function returns the name of the file used to create the calling process.</dd><dt>baseName</dt><dd>Type: System.Text.StringBuilder<br />A pointer to the buffer that receives the base name of the module. 

 If the base name is longer than maximum number of characters specified by the *size* parameter, the base name is truncated.</dd><dt>size</dt><dd>Type: System.UInt32<br />The size of the *baseName* buffer, in characters.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value specifies the length of the string copied to the buffer, in characters. 

 If the function fails, the return value is zero

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-getmodulebasenamea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-getmodulebasenamea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />