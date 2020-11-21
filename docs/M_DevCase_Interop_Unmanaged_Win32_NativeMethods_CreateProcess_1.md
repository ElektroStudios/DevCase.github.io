# NativeMethods.CreateProcess Method (String, StringBuilder, SecurityAttributes, SecurityAttributes, Boolean, CreateProcessFlags, IntPtr, String, ProcessStartupInfoEx, ProcessInformation)
 

Creates a new process and its primary thread. The new process runs in the security context of the calling process. 

 If the calling process is impersonating another user, the new process uses the token for the calling process, not the impersonation token. 

 To run the new process in the security context of the user represented by the impersonation token, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcessAsUser">CreateProcessAsUser(IntPtr, String, StringBuilder, SecurityAttributes, SecurityAttributes, Boolean, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcessWithLogon">CreateProcessWithLogon(String, String, String, ProcessLogonFlags, String, StringBuilder, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool CreateProcess(
	string applicationName,
	[OptionalAttribute] StringBuilder commandLine,
	ref SecurityAttributes refProcessAttribs,
	ref SecurityAttributes refThreadAttribs,
	bool inheritHandles,
	CreateProcessFlags createFlags,
	IntPtr environment,
	string currentDir,
	in ProcessStartupInfoEx refStartupInfoEx,
	out ProcessInformation refProcessInformation
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function CreateProcess ( 
	applicationName As String,
	<OptionalAttribute> <OutAttribute> commandLine As StringBuilder,
	ByRef refProcessAttribs As SecurityAttributes,
	ByRef refThreadAttribs As SecurityAttributes,
	inheritHandles As Boolean,
	createFlags As CreateProcessFlags,
	environment As IntPtr,
	currentDir As String,
	ByRef refStartupInfoEx As ProcessStartupInfoEx,
	<OutAttribute> ByRef refProcessInformation As ProcessInformation
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim applicationName As String
Dim commandLine As StringBuilder
Dim refProcessAttribs As SecurityAttributes
Dim refThreadAttribs As SecurityAttributes
Dim inheritHandles As Boolean
Dim createFlags As CreateProcessFlags
Dim environment As IntPtr
Dim currentDir As String
Dim refStartupInfoEx As ProcessStartupInfoEx
Dim refProcessInformation As ProcessInformation
Dim returnValue As Boolean

returnValue = NativeMethods.CreateProcess(applicationName, 
	commandLine, refProcessAttribs, 
	refThreadAttribs, inheritHandles, 
	createFlags, environment, currentDir, 
	refStartupInfoEx, refProcessInformation)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool CreateProcess(
	String^ applicationName, 
	[OptionalAttribute] [InAttribute] [OutAttribute] StringBuilder^ commandLine, 
	SecurityAttributes% refProcessAttribs, 
	SecurityAttributes% refThreadAttribs, 
	bool inheritHandles, 
	CreateProcessFlags createFlags, 
	IntPtr environment, 
	String^ currentDir, 
	[InAttribute] ProcessStartupInfoEx% refStartupInfoEx, 
	[OutAttribute] ProcessInformation% refProcessInformation
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member CreateProcess : 
        applicationName : string * 
        [<OptionalAttribute>] commandLine : StringBuilder byref * 
        refProcessAttribs : SecurityAttributes byref * 
        refThreadAttribs : SecurityAttributes byref * 
        inheritHandles : bool * 
        createFlags : CreateProcessFlags * 
        environment : IntPtr * 
        currentDir : string * 
        refStartupInfoEx : ProcessStartupInfoEx byref * 
        refProcessInformation : ProcessInformation byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>applicationName</dt><dd>Type: System.String<br />The name of the module to be executed. This module can be a Windows-based application. It can be some other type of module (for example, MS-DOS or OS/2) if the appropriate subsystem is available on the local computer. 

 The string can specify the full path and file name of the module to execute or it can specify a partial name. In the case of a partial name, the function uses the current drive and current directory to complete the specification. The function will not use the search path. This parameter must include the file name extension; no default extension is assumed. 

 The *applicationName* parameter can be NULL. In that case, the module name must be the first white space–delimited token in the *commandLine* string. If you are using a long file name that contains a space, use quoted strings to indicate where the file name ends and the arguments begin; otherwise, the file name is ambiguous. For example, consider the string "c:\program files\sub dir\program name". This string can be interpreted in a number of ways. The system tries to interpret the possibilities in the following order: 

 c:\program.exe, c:\program files\sub.exe, c:\program files\sub dir\program.exe, c:\program files\sub dir\program name.exe 

 If the executable module is a 16-bit application, *applicationName* should be NULL, and the string pointed to by *commandLine* should specify the executable module as well as its arguments. 

 To run a batch file, you must start the command interpreter; set *applicationName* to cmd.exe and set *commandLine* to the following arguments: "/c", plus the name of the batch file.</dd><dt>commandLine (Optional)</dt><dd>Type: System.Text.StringBuilder<br />The command line to be executed. 

 The maximum length of this string is Int16 (32,768 characters), including the Unicode terminating null character. 

 If *applicationName* is NULL, the module name portion of *commandLine* is limited to MAX_PATH characters. 

 The *commandLine* parameter can be NULL. In that case, the function uses the string pointed to by *applicationName* as the command line. 

 The Unicode version of this function, CreateProcessW, can modify the contents of this string. Therefore, this parameter cannot be a pointer to read-only memory (such as a const variable or a literal string). If this parameter is a constant string, the function may cause an access violation.</dd><dt>refProcessAttribs</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">DevCase.Interop.Unmanaged.Win32.Structures.SecurityAttributes</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">SecurityAttributes</a> structure that determines whether the returned handle to the new process object can be inherited by child processes. 

 If *refProcessAttribs* is NULL, the handle cannot be inherited. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes_SecurityDescriptor">SecurityDescriptor</a> member specifies a security descriptor for the new process. If *refProcessAttribs* is NULL or <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes_SecurityDescriptor">SecurityDescriptor</a> is Zero, the process gets a default security descriptor.</dd><dt>refThreadAttribs</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">DevCase.Interop.Unmanaged.Win32.Structures.SecurityAttributes</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">SecurityAttributes</a> structure that determines whether the returned handle to the new thread object can be inherited by child processes. 

 If *refThreadAttribs* is NULL, the handle cannot be inherited. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes_SecurityDescriptor">SecurityDescriptor</a> member specifies a security descriptor for the main thread. If *refThreadAttribs* is NULL or <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes_SecurityDescriptor">SecurityDescriptor</a> is Zero, the thread gets a default security descriptor.</dd><dt>inheritHandles</dt><dd>Type: System.Boolean<br />If this parameter is `true` (`True` in Visual Basic), each inheritable handle in the calling process is inherited by the new process. 

 If the parameter is `false` (`False` in Visual Basic), the handles are not inherited. 

 Note that inherited handles have the same value and access rights as the original handles.</dd><dt>createFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CreateProcessFlags">DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags</a><br />The flags that control the priority class and the creation of the process. 

 This parameter also controls the new process's priority class, which is used to determine the scheduling priorities of the process's threads.</dd><dt>environment</dt><dd>Type: System.IntPtr<br />A pointer to the environment block for the new process. 

 If this parameter is Zero, the new process uses the environment of the calling process. 

 An environment block consists of a null-terminated block of null-terminated strings. Each string is in the following form: 

`name=value\0`

 Because the equal sign is used as a separator, it must not be used in the name of an environment variable. 

 The ANSI version of this function, CreateProcessA, fails if the total size of the environment block for the process exceeds 32,767 characters.</dd><dt>currentDir</dt><dd>Type: System.String<br />The full path to the current directory for the process. The string can also specify a UNC path. 

 If this parameter is NULL, the new process will have the same current drive and directory as the calling process. (This feature is provided primarily for shells that need to start an application and specify its initial drive and working directory.)</dd><dt>refStartupInfoEx</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfoEx">DevCase.Interop.Unmanaged.Win32.Structures.ProcessStartupInfoEx</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfoEx">ProcessStartupInfoEx</a> structure. 

 To set extended attributes, use a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfoEx">ProcessStartupInfoEx</a> structure and specify <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CreateProcessFlags">ExtendedStartupInfoPresent</a> in the *createFlags* parameter.</dd><dt>refProcessInformation</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessInformation">DevCase.Interop.Unmanaged.Win32.Structures.ProcessInformation</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessInformation">ProcessInformation</a> structure that receives identification information about the new process.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error(). 

 Note that the function returns before the process has finished initialization. If a required DLL cannot be located or fails to initialize, the process is terminated. 

 To get the termination status of a process, call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetExitCodeProcess">GetExitCodeProcess(IntPtr, UInt32)</a>.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-createprocessa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-createprocessa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcess">CreateProcess Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />