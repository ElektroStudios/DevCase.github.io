# NativeMethods.DeleteVolumeMountPoint Method 
 

Deletes a drive letter or mounted folder.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool DeleteVolumeMountPoint(
	string volumeMountPoint
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function DeleteVolumeMountPoint ( 
	volumeMountPoint As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim volumeMountPoint As String
Dim returnValue As Boolean

returnValue = NativeMethods.DeleteVolumeMountPoint(volumeMountPoint)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool DeleteVolumeMountPoint(
	String^ volumeMountPoint
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member DeleteVolumeMountPoint : 
        volumeMountPoint : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>volumeMountPoint</dt><dd>Type: System.String<br />The drive letter or mounted folder to be deleted. 

 A trailing backslash is required, for example, "X:" or "Y:\MountX".</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-deletevolumemountpointw" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-deletevolumemountpointw</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />