# NativeMethods.GetApplicationRestartSettings Method 
 

Retrieves the restart information registered for the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true)]
public static HResult GetApplicationRestartSettings(
	IntPtr hProcess,
	StringBuilder commandline,
	ref uint refCommandlineSize,
	out ApplicationRestartFlags refFlags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Unicode, ExactSpelling := true>]
Public Shared Function GetApplicationRestartSettings ( 
	hProcess As IntPtr,
	commandline As StringBuilder,
	ByRef refCommandlineSize As UInteger,
	<OutAttribute> ByRef refFlags As ApplicationRestartFlags
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim commandline As StringBuilder
Dim refCommandlineSize As UInteger
Dim refFlags As ApplicationRestartFlags
Dim returnValue As HResult

returnValue = NativeMethods.GetApplicationRestartSettings(hProcess, 
	commandline, refCommandlineSize, 
	refFlags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Unicode, ExactSpelling = true)]
static HResult GetApplicationRestartSettings(
	IntPtr hProcess, 
	StringBuilder^ commandline, 
	unsigned int% refCommandlineSize, 
	[OutAttribute] ApplicationRestartFlags% refFlags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true)>]
static member GetApplicationRestartSettings : 
        hProcess : IntPtr * 
        commandline : StringBuilder * 
        refCommandlineSize : uint32 byref * 
        refFlags : ApplicationRestartFlags byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. This handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryRead</a> access right.</dd><dt>commandline</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that receives the restart command line specified by the application when it called the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegisterApplicationRestart">RegisterApplicationRestart(String, ApplicationRestartFlags)</a> function. 

 The maximum size of the command line, in characters, is RESTART_MAX_CMD_LINE. Can be NULL if *refCommandlineSize* is zero.</dd><dt>refCommandlineSize</dt><dd>Type: System.UInt32<br />On input, specifies the size of the *commandline* buffer, in characters. 

 If the buffer is not large enough to receive the command line, the function fails with HRESULT_FROM_WIN32(ERROR_INSUFFICIENT_BUFFER) and sets this parameter to the required buffer size, in characters. 

 On output, specifies the size of the buffer that was used. 

 To determine the required buffer size, set *commandline* to NULL and this parameter to zero. The size includes one for the null-terminator character. 

 Note that the function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>, not HRESULT_FROM_WIN32(ERROR_INSUFFICIENT_BUFFER) in this case.</dd><dt>refFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ApplicationRestartFlags">DevCase.Interop.Unmanaged.Win32.Enums.ApplicationRestartFlags</a><br />A pointer to a variable that receives the flags specified by the application when it called the RegisterApplicationRestart function.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getapplicationrestartsettings" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getapplicationrestartsettings</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />