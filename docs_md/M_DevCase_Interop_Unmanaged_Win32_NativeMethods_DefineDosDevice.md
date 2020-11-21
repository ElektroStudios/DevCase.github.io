# NativeMethods.DefineDosDevice Method 
 

Defines, redefines, or deletes MS-DOS device names.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool DefineDosDevice(
	DefineDosDeviceFlags flags,
	string deviceName,
	string targetPath
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Unicode, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function DefineDosDevice ( 
	flags As DefineDosDeviceFlags,
	deviceName As String,
	targetPath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim flags As DefineDosDeviceFlags
Dim deviceName As String
Dim targetPath As String
Dim returnValue As Boolean

returnValue = NativeMethods.DefineDosDevice(flags, 
	deviceName, targetPath)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Unicode, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool DefineDosDevice(
	DefineDosDeviceFlags flags, 
	String^ deviceName, 
	String^ targetPath
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member DefineDosDevice : 
        flags : DefineDosDeviceFlags * 
        deviceName : string * 
        targetPath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DefineDosDeviceFlags">DevCase.Interop.Unmanaged.Win32.Enums.DefineDosDeviceFlags</a><br />The controllable aspects of the DefineDosDevice(DefineDosDeviceFlags, String, String) function.</dd><dt>deviceName</dt><dd>Type: System.String<br />A pointer to an MS-DOS device name string specifying the device the function is defining, redefining, or deleting. 

 The device name string must not have a colon as the last character, unless a drive letter is being defined, redefined, or deleted. 

 For example, drive 'C' would be the string "C:". In no case is a trailing backslash ("\") allowed.</dd><dt>targetPath</dt><dd>Type: System.String<br />A pointer to a path string that will implement this device. 

 The string is an MS-DOS path string unless the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DefineDosDeviceFlags">RawTargetPath</a> flag is specified, in which case this string is a path string.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error(). 



## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-definedosdevicew" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-definedosdevicew</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />