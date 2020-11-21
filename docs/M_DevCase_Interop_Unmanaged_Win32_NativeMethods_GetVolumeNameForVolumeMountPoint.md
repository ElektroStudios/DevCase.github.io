# NativeMethods.GetVolumeNameForVolumeMountPoint Method 
 

Retrieves a volume GUID path for the volume that is associated with the specified volume mount point ( drive letter, volume GUID path, or mounted folder).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool GetVolumeNameForVolumeMountPoint(
	string volumeMountPoint,
	StringBuilder volumeName,
	uint bufferLength
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetVolumeNameForVolumeMountPoint ( 
	volumeMountPoint As String,
	volumeName As StringBuilder,
	bufferLength As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim volumeMountPoint As String
Dim volumeName As StringBuilder
Dim bufferLength As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.GetVolumeNameForVolumeMountPoint(volumeMountPoint, 
	volumeName, bufferLength)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool GetVolumeNameForVolumeMountPoint(
	String^ volumeMountPoint, 
	StringBuilder^ volumeName, 
	unsigned int bufferLength
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetVolumeNameForVolumeMountPoint : 
        volumeMountPoint : string * 
        volumeName : StringBuilder * 
        bufferLength : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>volumeMountPoint</dt><dd>Type: System.String<br />A pointer to a string that contains the path of a mounted folder (for example, "Y:\MountX") or a drive letter (for example, "X:"). 

 The string must end with a trailing backslash ('').</dd><dt>volumeName</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a string that receives the volume GUID path. 

 This path is of the form "\?\Volume{GUID}" where GUID is a GUID that identifies the volume. 

 If there is more than one volume GUID path for the volume, only the first one in the mount manager's cache is returned.</dd><dt>bufferLength</dt><dd>Type: System.UInt32<br />The length of the output buffer. 

 A reasonable size for the buffer to accommodate the largest possible volume GUID path is 50 characters.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getvolumenameforvolumemountpointw" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getvolumenameforvolumemountpointw</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />