# NativeMethods.GetVolumePathName Method 
 

Retrieves the volume mount point where the specified path is mounted.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool GetVolumePathName(
	string fileName,
	StringBuilder volumePathName,
	uint bufferLength
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetVolumePathName ( 
	fileName As String,
	volumePathName As StringBuilder,
	bufferLength As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim fileName As String
Dim volumePathName As StringBuilder
Dim bufferLength As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.GetVolumePathName(fileName, 
	volumePathName, bufferLength)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool GetVolumePathName(
	String^ fileName, 
	StringBuilder^ volumePathName, 
	unsigned int bufferLength
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetVolumePathName : 
        fileName : string * 
        volumePathName : StringBuilder * 
        bufferLength : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: System.String<br />A pointer to the input path string. Both absolute and relative file and directory names, for example "..", are acceptable in this path. 

 If you specify a relative directory or file name without a volume qualifier, GetVolumePathName(String, StringBuilder, UInt32) returns the drive letter of the boot volume. 

 If this parameter is an empty string, "", the function fails but the last error is set to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>.</dd><dt>volumePathName</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a string that receives the volume mount point for the input path.</dd><dt>bufferLength</dt><dd>Type: System.UInt32<br />The length of the output buffer.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getvolumepathnamew" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getvolumepathnamew</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />