# NativeMethods.AppPolicyGetCreateFileAccess Method 
 

Retrieves a value indicating whether a process has full or restricted access to the I/O devices (file, file stream, directory, physical disk, volume, console buffer, tape drive, communications resource, mailslot, and pipe).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static Win32ErrorCode AppPolicyGetCreateFileAccess(
	IntPtr processToken,
	out AppPolicyCreateFileAccess refPolicy
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function AppPolicyGetCreateFileAccess ( 
	processToken As IntPtr,
	<OutAttribute> ByRef refPolicy As AppPolicyCreateFileAccess
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim processToken As IntPtr
Dim refPolicy As AppPolicyCreateFileAccess
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.AppPolicyGetCreateFileAccess(processToken, 
	refPolicy)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static Win32ErrorCode AppPolicyGetCreateFileAccess(
	IntPtr processToken, 
	[OutAttribute] AppPolicyCreateFileAccess% refPolicy
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member AppPolicyGetCreateFileAccess : 
        processToken : IntPtr * 
        refPolicy : AppPolicyCreateFileAccess byref -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>processToken</dt><dd>Type: System.IntPtr<br />A handle that identifies the access token for a process.</dd><dt>refPolicy</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_AppPolicyCreateFileAccess">DevCase.Interop.Unmanaged.Win32.Enums.AppPolicyCreateFileAccess</a><br />When the function returns successfully, *refPolicy* contains a value indicating whether the process has full or restricted access to the I/O devices.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If the function succeeds, the function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. 

 If no known create file access policy was found for the process token, the function raises a STATUS_ASSERTION_FAILURE exception and returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_NOT_FOUND</a>. 

 If either *processToken* or *refPolicy* are null, the function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_INVALID_PARAMETER</a>.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/appmodel/nf-appmodel-apppolicygetcreatefileaccess" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/appmodel/nf-appmodel-apppolicygetcreatefileaccess</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />