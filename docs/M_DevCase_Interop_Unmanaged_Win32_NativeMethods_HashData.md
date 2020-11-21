# NativeMethods.HashData Method 
 

Hashes an array of data.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", ExactSpelling = true)]
public static HResult HashData(
	IntPtr data,
	uint dataSize,
	IntPtr hash,
	uint hashSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", ExactSpelling := true>]
Public Shared Function HashData ( 
	data As IntPtr,
	dataSize As UInteger,
	hash As IntPtr,
	hashSize As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim data As IntPtr
Dim dataSize As UInteger
Dim hash As IntPtr
Dim hashSize As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.HashData(data, 
	dataSize, hash, hashSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", ExactSpelling = true)]
static HResult HashData(
	IntPtr data, 
	unsigned int dataSize, 
	IntPtr hash, 
	unsigned int hashSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", ExactSpelling = true)>]
static member HashData : 
        data : IntPtr * 
        dataSize : uint32 * 
        hash : IntPtr * 
        hashSize : uint32 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>data</dt><dd>Type: System.IntPtr<br />A pointer to the data array.</dd><dt>dataSize</dt><dd>Type: System.UInt32<br />The number of elements in the array at *data*.</dd><dt>hash</dt><dd>Type: System.IntPtr<br />A pointer to a value that, when this function returns successfully, receives the hashed array.</dd><dt>hashSize</dt><dd>Type: System.UInt32<br />The number of elements in *hash*. It should be no larger than 256.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-hashdata" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-hashdata</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />