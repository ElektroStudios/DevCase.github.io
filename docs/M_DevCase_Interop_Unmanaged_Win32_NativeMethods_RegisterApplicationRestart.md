# NativeMethods.RegisterApplicationRestart Method 
 

Registers the active instance of an application for restart.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true)]
public static HResult RegisterApplicationRestart(
	string commandline,
	ApplicationRestartFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Unicode, ExactSpelling := true>]
Public Shared Function RegisterApplicationRestart ( 
	commandline As String,
	flags As ApplicationRestartFlags
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim commandline As String
Dim flags As ApplicationRestartFlags
Dim returnValue As HResult

returnValue = NativeMethods.RegisterApplicationRestart(commandline, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Unicode, ExactSpelling = true)]
static HResult RegisterApplicationRestart(
	String^ commandline, 
	ApplicationRestartFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true)>]
static member RegisterApplicationRestart : 
        commandline : string * 
        flags : ApplicationRestartFlags -> HResult 

```


#### Parameters
&nbsp;<dl><dt>commandline</dt><dd>Type: System.String<br />A pointer to a Unicode string that specifies the command-line arguments for the application when it is restarted. 

 The maximum size of the command line that you can specify is RESTART_MAX_CMD_LINE characters. 

 Do not include the name of the executable in the command line; this function adds it for you. 

 If this parameter is NULL or an empty string, the previously registered command line is removed. 

 If the argument contains spaces, use quotes around the argument.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ApplicationRestartFlags">DevCase.Interop.Unmanaged.Win32.Enums.ApplicationRestartFlags</a><br />Application restart flags.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error codes on fail.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-registerapplicationrestart" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-registerapplicationrestart</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />