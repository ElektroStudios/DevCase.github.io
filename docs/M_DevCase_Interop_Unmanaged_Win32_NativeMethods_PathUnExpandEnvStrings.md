# NativeMethods.PathUnExpandEnvStrings Method 
 

Replaces certain folder names in a fully qualified path with their associated environment string.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool PathUnExpandEnvStrings(
	string path,
	StringBuilder buffer,
	uint bufferSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function PathUnExpandEnvStrings ( 
	path As String,
	buffer As StringBuilder,
	bufferSize As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim path As String
Dim buffer As StringBuilder
Dim bufferSize As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.PathUnExpandEnvStrings(path, 
	buffer, bufferSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool PathUnExpandEnvStrings(
	String^ path, 
	StringBuilder^ buffer, 
	unsigned int bufferSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PathUnExpandEnvStrings : 
        path : string * 
        buffer : StringBuilder * 
        bufferSize : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.String<br />A pointer to a null-terminated string of maximum length MAX_PATH that contains the path to be unexpanded.</dd><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that, when this method returns successfully, receives the unexpanded string. 

 The size of this buffer must be set to MAX_PATH to ensure that it is large enough to hold the returned string.</dd><dt>bufferSize</dt><dd>Type: System.UInt32<br />The size, in characters, in the *buffer* parameter.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathunexpandenvstringsa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathunexpandenvstringsa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />