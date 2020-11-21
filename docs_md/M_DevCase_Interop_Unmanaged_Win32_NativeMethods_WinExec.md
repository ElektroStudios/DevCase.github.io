# NativeMethods.WinExec Method 
 

**Note: This API is now obsolete.**

Runs the specified application. 

 Note: This function is provided only for compatibility with 16-bit Windows. Applications should use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcess">CreateProcess(String, StringBuilder, SecurityAttributes, SecurityAttributes, Boolean, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
[ObsoleteAttribute("Note: This function is provided only for compatibility with 16-bit Windows. Applications should use the 'CreateProcess' function.", 
	false)]
public static uint WinExec(
	string cmdLine,
	NativeWindowState cmdShow
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true>]
<ObsoleteAttribute("Note: This function is provided only for compatibility with 16-bit Windows. Applications should use the 'CreateProcess' function.", 
	false)>
Public Shared Function WinExec ( 
	cmdLine As String,
	cmdShow As NativeWindowState
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim cmdLine As String
Dim cmdShow As NativeWindowState
Dim returnValue As UInteger

returnValue = NativeMethods.WinExec(cmdLine, 
	cmdShow)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
[ObsoleteAttribute(L"Note: This function is provided only for compatibility with 16-bit Windows. Applications should use the 'CreateProcess' function.", 
	false)]
static unsigned int WinExec(
	[InAttribute] String^ cmdLine, 
	NativeWindowState cmdShow
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)>]
[<ObsoleteAttribute("Note: This function is provided only for compatibility with 16-bit Windows. Applications should use the 'CreateProcess' function.", 
	false)>]
static member WinExec : 
        cmdLine : string * 
        cmdShow : NativeWindowState -> uint32 

```


#### Parameters
&nbsp;<dl><dt>cmdLine</dt><dd>Type: System.String<br />The command line (file name plus optional parameters) for the application to be executed. If the name of the executable file in the lpCmdLine parameter does not contain a directory path, the system searches for the executable file in this sequence: 

 1. The directory from which the application loaded. 

 2. The current directory. 

 3. The Windows system directory. The GetSystemDirectory function retrieves the path of this directory. 

 4. The Windows directory. The GetWindowsDirectory function retrieves the path of this directory. 

 5. The directories listed in the PATH environment variable.</dd><dt>cmdShow</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NativeWindowState">DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState</a><br />The display options.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is greater than 31. 

 If the function fails, the return value is one of the following error values: 0 (zero): The system is out of memory or resources. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_BAD_FORMAT</a><a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_FILE_NOT_FOUND</a><a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_PATH_NOT_FOUND</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-winexec" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-winexec</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />