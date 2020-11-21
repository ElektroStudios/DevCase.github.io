# NativeMethods.GetLongPathName Method 
 

Converts the specified path to its long form.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GetLongPathName(
	string shortPath,
	StringBuilder longPath,
	uint bufferLen
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetLongPathName ( 
	shortPath As String,
	longPath As StringBuilder,
	bufferLen As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim shortPath As String
Dim longPath As StringBuilder
Dim bufferLen As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetLongPathName(shortPath, 
	longPath, bufferLen)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GetLongPathName(
	String^ shortPath, 
	StringBuilder^ longPath, 
	unsigned int bufferLen
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetLongPathName : 
        shortPath : string * 
        longPath : StringBuilder * 
        bufferLen : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>shortPath</dt><dd>Type: System.String<br />The path to be converted</dd><dt>longPath</dt><dd>Type: System.Text.StringBuilder<br />A pointer to the buffer to receive the long path.</dd><dt>bufferLen</dt><dd>Type: System.UInt32<br />The size of the buffer lpszLongPath points to.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the length of the string copied to *longPath*, not including the terminating null character. 

 If the *bufferLen* buffer is too small to contain the path, the return value is the size of the buffer that is required to hold the path and the terminating null character. 

 If the function fails for any other reason, such as if the file does not exist, the return value is zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getlongpathnamea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getlongpathnamea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />