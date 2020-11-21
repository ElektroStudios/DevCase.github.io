# NativeMethods.GetShortPathName Method 
 

Retrieves the short path form of the specified path.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GetShortPathName(
	string longPath,
	StringBuilder shortPath,
	uint bufferLen
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetShortPathName ( 
	longPath As String,
	shortPath As StringBuilder,
	bufferLen As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim longPath As String
Dim shortPath As StringBuilder
Dim bufferLen As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetShortPathName(longPath, 
	shortPath, bufferLen)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GetShortPathName(
	String^ longPath, 
	StringBuilder^ shortPath, 
	unsigned int bufferLen
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetShortPathName : 
        longPath : string * 
        shortPath : StringBuilder * 
        bufferLen : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>longPath</dt><dd>Type: System.String<br />The path string.</dd><dt>shortPath</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer to receive the null-terminated short form of the path that *longPath* parameter specifies. 

 Passing a null reference (`Nothing` in Visual Basic) for this parameter and zero for *bufferLen* parameter, will always return the required buffer size for a specified *longPath* parameter.</dd><dt>bufferLen</dt><dd>Type: System.UInt32<br />The size of the buffer that *shortPath* points to. 

 Set this parameter to zero if *shortPath* is set to a null reference (`Nothing` in Visual Basic).</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the length of the string that is copied to *shortPath*, not including the terminating null character. 

 If the *shortPath* buffer is too small to contain the path, the return value is the size of the buffer that is required to hold the path and the terminating null character. 

 If the function fails for any other reason, the return value is zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getshortpathnamew" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getshortpathnamew</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />