# NativeMethods.ImpersonateLoggedOnUser Method 
 

Lets the calling thread impersonate the security context of a logged-on user. The user is represented by a token handle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", ExactSpelling = true, SetLastError = true)]
public static bool ImpersonateLoggedOnUser(
	IntPtr hToken
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ImpersonateLoggedOnUser ( 
	hToken As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hToken As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.ImpersonateLoggedOnUser(hToken)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", ExactSpelling = true, SetLastError = true)]
static bool ImpersonateLoggedOnUser(
	IntPtr hToken
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", ExactSpelling = true, SetLastError = true)>]
static member ImpersonateLoggedOnUser : 
        hToken : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hToken</dt><dd>Type: System.IntPtr<br />A handle to a primary or impersonation access token that represents a logged-on user. 

 This can be a token handle returned by a call to LogonUser, CreateRestrictedToken, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DuplicateToken">DuplicateToken(IntPtr, SecurityImpersonationLevel, IntPtr)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DuplicateTokenEx">DuplicateTokenEx(IntPtr, TokenAccess, SecurityAttributes, SecurityImpersonationLevel, TokenType, IntPtr)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenProcessToken">OpenProcessToken(SafeProcessHandle, TokenAccess, IntPtr)</a>, or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenThreadToken">OpenThreadToken(IntPtr, TokenAccess, Boolean, IntPtr)</a> functions. 

 If *hToken* is a handle to a primary token, the token must have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Query</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Duplicate</a> access. 

 If *hToken* is a handle to an impersonation token, the token must have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Query</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Impersonate</a> access.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/securitybaseapi/nf-securitybaseapi-impersonateloggedonuser" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/securitybaseapi/nf-securitybaseapi-impersonateloggedonuser</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />