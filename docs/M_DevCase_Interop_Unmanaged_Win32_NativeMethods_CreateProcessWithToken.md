# NativeMethods.CreateProcessWithToken Method 
 

Creates a new process and its primary thread. The new process runs in the security context of the specified token. It can optionally load the user profile for the specified user. 

 The process that calls CreateProcessWithToken(IntPtr, ProcessLogonFlags, String, StringBuilder, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation) must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessPrivileges">ImpersonatePrivilege</a> privilege. If this function fails with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_PRIVILEGE_NOT_HELD</a> (1314), use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcessAsUser">CreateProcessAsUser(IntPtr, String, StringBuilder, SecurityAttributes, SecurityAttributes, Boolean, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcessWithLogon">CreateProcessWithLogon(String, String, String, ProcessLogonFlags, String, StringBuilder, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a> function instead. Typically, the process that calls. 

 Generally, it is best to use <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcessWithLogon">CreateProcessWithLogon(String, String, String, ProcessLogonFlags, String, StringBuilder, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a> to create a process with alternate credentials.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", EntryPoint = "CreateProcessWithTokenW", 
	CharSet = CharSet.Auto, BestFitMapping = false, ThrowOnUnmappableChar = true, 
	SetLastError = true)]
public static bool CreateProcessWithToken(
	IntPtr hToken,
	ProcessLogonFlags logonFlags,
	string applicationName,
	[OptionalAttribute] StringBuilder commandLine,
	CreateProcessFlags createFlags,
	IntPtr environment,
	string currentDir,
	in ProcessStartupInfo refStartupInfo,
	out ProcessInformation refProcessInformation
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", EntryPoint := "CreateProcessWithTokenW", 
	CharSet := CharSet.Auto, BestFitMapping := false, ThrowOnUnmappableChar := true, 
	SetLastError := true>]
Public Shared Function CreateProcessWithToken ( 
	hToken As IntPtr,
	logonFlags As ProcessLogonFlags,
	applicationName As String,
	<OptionalAttribute> <OutAttribute> commandLine As StringBuilder,
	createFlags As CreateProcessFlags,
	environment As IntPtr,
	currentDir As String,
	ByRef refStartupInfo As ProcessStartupInfo,
	<OutAttribute> ByRef refProcessInformation As ProcessInformation
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hToken As IntPtr
Dim logonFlags As ProcessLogonFlags
Dim applicationName As String
Dim commandLine As StringBuilder
Dim createFlags As CreateProcessFlags
Dim environment As IntPtr
Dim currentDir As String
Dim refStartupInfo As ProcessStartupInfo
Dim refProcessInformation As ProcessInformation
Dim returnValue As Boolean

returnValue = NativeMethods.CreateProcessWithToken(hToken, 
	logonFlags, applicationName, commandLine, 
	createFlags, environment, currentDir, 
	refStartupInfo, refProcessInformation)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", EntryPoint = L"CreateProcessWithTokenW", 
	CharSet = CharSet::Auto, BestFitMapping = false, ThrowOnUnmappableChar = true, 
	SetLastError = true)]
static bool CreateProcessWithToken(
	IntPtr hToken, 
	ProcessLogonFlags logonFlags, 
	String^ applicationName, 
	[OptionalAttribute] [InAttribute] [OutAttribute] StringBuilder^ commandLine, 
	CreateProcessFlags createFlags, 
	IntPtr environment, 
	String^ currentDir, 
	[InAttribute] ProcessStartupInfo% refStartupInfo, 
	[OutAttribute] ProcessInformation% refProcessInformation
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", EntryPoint = "CreateProcessWithTokenW", 
	CharSet = CharSet.Auto, BestFitMapping = false, ThrowOnUnmappableChar = true, 
	SetLastError = true)>]
static member CreateProcessWithToken : 
        hToken : IntPtr * 
        logonFlags : ProcessLogonFlags * 
        applicationName : string * 
        [<OptionalAttribute>] commandLine : StringBuilder byref * 
        createFlags : CreateProcessFlags * 
        environment : IntPtr * 
        currentDir : string * 
        refStartupInfo : ProcessStartupInfo byref * 
        refProcessInformation : ProcessInformation byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hToken</dt><dd>Type: System.IntPtr<br />A handle to the primary token that represents a user. The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Query</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Duplicate</a>, and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">AssignPrimary</a> access rights. 

 The user represented by the token must have read and execute access to the application specified by the *applicationName* or the *commandLine* parameter. 

 To get a primary token that represents the specified user, call the LogonUser function. Alternatively, you can call the DuplicateTokenEx function to convert an impersonation token into a primary token. This allows a server application that is impersonating a client to create a process that has the security context of the client.</dd><dt>logonFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessLogonFlags">DevCase.Interop.Unmanaged.Win32.Enums.ProcessLogonFlags</a><br />The logon option.</dd><dt>applicationName</dt><dd>Type: System.String<br />The name of the module to be executed. This module can be a Windows-based application. It can be some other type of module (for example, MS-DOS or OS/2) if the appropriate subsystem is available on the local computer. 

 The string can specify the full path and file name of the module to execute or it can specify a partial name. In the case of a partial name, the function uses the current drive and current directory to complete the specification. The function will not use the search path. This parameter must include the file name extension; no default extension is assumed. 

 The *applicationName* parameter can be NULL. In that case, the module name must be the first white space–delimited token in the *commandLine* string. If you are using a long file name that contains a space, use quoted strings to indicate where the file name ends and the arguments begin; otherwise, the file name is ambiguous. For example, consider the string "c:\program files\sub dir\program name". This string can be interpreted in a number of ways. The system tries to interpret the possibilities in the following order: 

 c:\program.exe, c:\program files\sub.exe, c:\program files\sub dir\program.exe, c:\program files\sub dir\program name.exe 

 If the executable module is a 16-bit application, *applicationName* should be NULL, and the string pointed to by *commandLine* should specify the executable module as well as its arguments. 

 To run a batch file, you must start the command interpreter; set *applicationName* to cmd.exe and set *commandLine* to the following arguments: "/c", plus the name of the batch file.</dd><dt>commandLine (Optional)</dt><dd>Type: System.Text.StringBuilder<br />The command line to be executed. 

 The maximum length of this string is Int16 (32,768 characters), including the Unicode terminating null character. 

 If *applicationName* is NULL, the module name portion of *commandLine* is limited to MAX_PATH characters. 

 The *commandLine* parameter can be NULL. In that case, the function uses the string pointed to by *applicationName* as the command line. 

 The Unicode version of this function, CreateProcessW, can modify the contents of this string. Therefore, this parameter cannot be a pointer to read-only memory (such as a const variable or a literal string). If this parameter is a constant string, the function may cause an access violation.</dd><dt>createFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CreateProcessFlags">DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags</a><br />The flags that control the priority class and the creation of the process. 

 This parameter also controls the new process's priority class, which is used to determine the scheduling priorities of the process's threads.</dd><dt>environment</dt><dd>Type: System.IntPtr<br />A pointer to the environment block for the new process. 

 If this parameter is Zero, the new process uses the environment of the calling process. 

 An environment block consists of a null-terminated block of null-terminated strings. Each string is in the following form: 

`name=value\0`

 Because the equal sign is used as a separator, it must not be used in the name of an environment variable. 

 The ANSI version of this function, CreateProcessA, fails if the total size of the environment block for the process exceeds 32,767 characters.</dd><dt>currentDir</dt><dd>Type: System.String<br />The full path to the current directory for the process. The string can also specify a UNC path. 

 If this parameter is NULL, the new process will have the same current drive and directory as the calling process. (This feature is provided primarily for shells that need to start an application and specify its initial drive and working directory.)</dd><dt>refStartupInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo">DevCase.Interop.Unmanaged.Win32.Structures.ProcessStartupInfo</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo">ProcessStartupInfo</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfoEx">ProcessStartupInfoEx</a> structure. 

 To set extended attributes, use a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfoEx">ProcessStartupInfoEx</a> structure and specify <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CreateProcessFlags">ExtendedStartupInfoPresent</a> in the *createFlags* parameter.</dd><dt>refProcessInformation</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessInformation">DevCase.Interop.Unmanaged.Win32.Structures.ProcessInformation</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessInformation">ProcessInformation</a> structure that receives identification information about the new process.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error(). 

 Note that the function returns before the process has finished initialization. If a required DLL cannot be located or fails to initialize, the process is terminated. 

 To get the termination status of a process, call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetExitCodeProcess">GetExitCodeProcess(IntPtr, UInt32)</a>.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-createprocesswithtokenw" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-createprocesswithtokenw</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />