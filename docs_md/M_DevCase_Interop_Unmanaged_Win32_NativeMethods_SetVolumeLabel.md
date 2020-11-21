# NativeMethods.SetVolumeLabel Method 
 

Sets the label of a file system volume.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool SetVolumeLabel(
	string rootPathName,
	string volumeName
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function SetVolumeLabel ( 
	rootPathName As String,
	volumeName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim rootPathName As String
Dim volumeName As String
Dim returnValue As Boolean

returnValue = NativeMethods.SetVolumeLabel(rootPathName, 
	volumeName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool SetVolumeLabel(
	String^ rootPathName, 
	String^ volumeName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member SetVolumeLabel : 
        rootPathName : string * 
        volumeName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>rootPathName</dt><dd>Type: System.String<br />A pointer to a string that contains the volume's drive letter (for example, X:) or the path of a mounted folder that is associated with the volume (for example, Y:\MountX). 

 The string must end with a trailing backslash (''). 

 If this parameter is a null reference (`Nothing` in Visual Basic), the root of the current directory is used.</dd><dt>volumeName</dt><dd>Type: System.String<br />A pointer to a string that contains the new label for the volume. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the function deletes any existing label from the specified volume and does not assign a new label.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-setvolumelabela" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-setvolumelabela</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />