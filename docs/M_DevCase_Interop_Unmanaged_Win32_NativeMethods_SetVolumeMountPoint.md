# NativeMethods.SetVolumeMountPoint Method 
 

Associates a volume with a drive letter or a directory on another volume.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool SetVolumeMountPoint(
	string volumeMountPoint,
	string volumeName
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function SetVolumeMountPoint ( 
	volumeMountPoint As String,
	volumeName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim volumeMountPoint As String
Dim volumeName As String
Dim returnValue As Boolean

returnValue = NativeMethods.SetVolumeMountPoint(volumeMountPoint, 
	volumeName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool SetVolumeMountPoint(
	String^ volumeMountPoint, 
	String^ volumeName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member SetVolumeMountPoint : 
        volumeMountPoint : string * 
        volumeName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>volumeMountPoint</dt><dd>Type: System.String<br />The user-mode path to be associated with the volume. This may be a drive letter (for example, "X:") or a directory on another volume (for example, "Y:\MountX"). 

 The string must end with a trailing backslash (''). 

 If the *volumeMountPoint* parameter contains a path to a mounted folder, last error returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_DIR_NOT_EMPTY</a>, even if the directory is empty.</dd><dt>volumeName</dt><dd>Type: System.String<br />A volume GUID path for the volume. 

 This string must be of the form `"\?\Volume{GUID}"` where GUID is a GUID that identifies the volume. 

 The "\?" turns off path parsing and is ignored as part of the path.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-setvolumemountpointa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-setvolumemountpointa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />