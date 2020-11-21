# NativeMethods.GetVolumePathNamesForVolumeName Method 
 

Retrieves a list of drive letters and mounted folder paths for the specified volume.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool GetVolumePathNamesForVolumeName(
	string volumeName,
	StringBuilder volumePathNames,
	uint bufferLength,
	out uint refReturnLength
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetVolumePathNamesForVolumeName ( 
	volumeName As String,
	volumePathNames As StringBuilder,
	bufferLength As UInteger,
	<OutAttribute> ByRef refReturnLength As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim volumeName As String
Dim volumePathNames As StringBuilder
Dim bufferLength As UInteger
Dim refReturnLength As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.GetVolumePathNamesForVolumeName(volumeName, 
	volumePathNames, bufferLength, refReturnLength)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool GetVolumePathNamesForVolumeName(
	String^ volumeName, 
	StringBuilder^ volumePathNames, 
	unsigned int bufferLength, 
	[OutAttribute] unsigned int% refReturnLength
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetVolumePathNamesForVolumeName : 
        volumeName : string * 
        volumePathNames : StringBuilder * 
        bufferLength : uint32 * 
        refReturnLength : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>volumeName</dt><dd>Type: System.String<br />A volume GUID path for the volume. 

 A volume GUID path is of the form `"\?\Volume{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"`.</dd><dt>volumePathNames</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that receives the list of drive letters and mounted folder paths. 

 The list is an array of null-terminated strings terminated by an additional NULL character. 

 If the buffer is not large enough to hold the complete list, the buffer holds as much of the list as possible.</dd><dt>bufferLength</dt><dd>Type: System.UInt32<br />The length of the *volumePathNames* buffer, including all NULL characters. 

 If the buffer is not large enough to hold the complete list, the error code is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_MORE_DATA</a> and the *refReturnLength* parameter receives the required buffer size.</dd><dt>refReturnLength</dt><dd>Type: System.UInt32<br />If the call is successful, this parameter is the number of characters copied to the *volumePathNames* buffer. 

 Otherwise, this parameter is the size of the buffer required to hold the complete list.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getvolumepathnamesforvolumenamew" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getvolumepathnamesforvolumenamew</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />