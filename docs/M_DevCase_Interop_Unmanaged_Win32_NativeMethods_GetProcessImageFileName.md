# NativeMethods.GetProcessImageFileName Method 
 

Retrieves the name of the executable file for the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("PsApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GetProcessImageFileName(
	IntPtr hProcess,
	StringBuilder imageFileName,
	uint size
)
```

**VB**<br />
``` VB
<DllImportAttribute("PsApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetProcessImageFileName ( 
	hProcess As IntPtr,
	imageFileName As StringBuilder,
	size As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim imageFileName As StringBuilder
Dim size As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetProcessImageFileName(hProcess, 
	imageFileName, size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"PsApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GetProcessImageFileName(
	IntPtr hProcess, 
	StringBuilder^ imageFileName, 
	unsigned int size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("PsApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetProcessImageFileName : 
        hProcess : IntPtr * 
        imageFileName : StringBuilder * 
        size : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryLimitedInformation</a> access right.</dd><dt>imageFileName</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that receives the full path to the executable file.</dd><dt>size</dt><dd>Type: System.UInt32<br />The size of the lpImageFileName buffer, in characters.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value specifies the length of the string copied to the buffer. 

 If the function fails, the return value is zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-getprocessimagefilenamea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-getprocessimagefilenamea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />