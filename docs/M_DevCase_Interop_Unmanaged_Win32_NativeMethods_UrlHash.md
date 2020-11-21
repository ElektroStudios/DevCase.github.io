# NativeMethods.UrlHash Method 
 

Hashes a URL string.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult UrlHash(
	string url,
	IntPtr hash,
	uint hashSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function UrlHash ( 
	url As String,
	hash As IntPtr,
	hashSize As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim hash As IntPtr
Dim hashSize As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.UrlHash(url, hash, 
	hashSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult UrlHash(
	String^ url, 
	IntPtr hash, 
	unsigned int hashSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member UrlHash : 
        url : string * 
        hash : IntPtr * 
        hashSize : uint32 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />A null-terminated string of maximum length INTERNET_MAX_URL_LENGTH that contains the URL.</dd><dt>hash</dt><dd>Type: System.IntPtr<br />A pointere to a buffer that, when this function returns successfully, receives the hashed array.</dd><dt>hashSize</dt><dd>Type: System.UInt32<br />The number of elements in the array at *hash*. It should be no larger than 256.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-urlhashw" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-urlhashw</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />