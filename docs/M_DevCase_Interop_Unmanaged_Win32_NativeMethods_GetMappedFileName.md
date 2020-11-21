# NativeMethods.GetMappedFileName Method 
 

Checks whether the specified address is within a memory-mapped file in the address space of the specified process. If so, the function returns the name of the memory-mapped file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("PsApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GetMappedFileName(
	IntPtr hProcess,
	IntPtr address,
	StringBuilder filename,
	uint size
)
```

**VB**<br />
``` VB
<DllImportAttribute("PsApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetMappedFileName ( 
	hProcess As IntPtr,
	address As IntPtr,
	filename As StringBuilder,
	size As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim address As IntPtr
Dim filename As StringBuilder
Dim size As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetMappedFileName(hProcess, 
	address, filename, size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"PsApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GetMappedFileName(
	IntPtr hProcess, 
	IntPtr address, 
	StringBuilder^ filename, 
	unsigned int size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("PsApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetMappedFileName : 
        hProcess : IntPtr * 
        address : IntPtr * 
        filename : StringBuilder * 
        size : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryRead</a> access right.</dd><dt>address</dt><dd>Type: System.IntPtr<br />The address to be verified.</dd><dt>filename</dt><dd>Type: System.Text.StringBuilder<br />A pointer to the buffer that receives the name of the memory-mapped file to which the address specified by lpv belongs.</dd><dt>size</dt><dd>Type: System.UInt32<br />The size of the *filename* buffer, in characters.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value specifies the length of the string copied to the buffer, in characters. 

 If the function fails, the return value is zero

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-getmappedfilenamea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-getmappedfilenamea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />