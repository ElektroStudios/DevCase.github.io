# NativeMethods.DuplicateTokenEx Method 
 

Creates a new access token that duplicates an existing token. 

 This function can create either a primary token or an impersonation token.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", SetLastError = true)]
public static bool DuplicateTokenEx(
	IntPtr existingToken,
	TokenAccess desiredAccess,
	SecurityAttributes tokenAttributes,
	SecurityImpersonationLevel impersonationLevel,
	TokenType tokenType,
	out IntPtr refNewToken
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", SetLastError := true>]
Public Shared Function DuplicateTokenEx ( 
	existingToken As IntPtr,
	desiredAccess As TokenAccess,
	tokenAttributes As SecurityAttributes,
	impersonationLevel As SecurityImpersonationLevel,
	tokenType As TokenType,
	<OutAttribute> ByRef refNewToken As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim existingToken As IntPtr
Dim desiredAccess As TokenAccess
Dim tokenAttributes As SecurityAttributes
Dim impersonationLevel As SecurityImpersonationLevel
Dim tokenType As TokenType
Dim refNewToken As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.DuplicateTokenEx(existingToken, 
	desiredAccess, tokenAttributes, 
	impersonationLevel, tokenType, refNewToken)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", SetLastError = true)]
static bool DuplicateTokenEx(
	IntPtr existingToken, 
	TokenAccess desiredAccess, 
	SecurityAttributes tokenAttributes, 
	SecurityImpersonationLevel impersonationLevel, 
	TokenType tokenType, 
	[OutAttribute] IntPtr% refNewToken
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", SetLastError = true)>]
static member DuplicateTokenEx : 
        existingToken : IntPtr * 
        desiredAccess : TokenAccess * 
        tokenAttributes : SecurityAttributes * 
        impersonationLevel : SecurityImpersonationLevel * 
        tokenType : TokenType * 
        refNewToken : IntPtr byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>existingToken</dt><dd>Type: System.IntPtr<br />A handle to an access token opened with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Duplicate</a> access.</dd><dt>desiredAccess</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess</a><br />Specifies the requested access rights for the new token. 

 The DuplicateTokenEx(IntPtr, TokenAccess, SecurityAttributes, SecurityImpersonationLevel, TokenType, IntPtr) function compares the requested access rights with the existing token's discretionary access control list (DACL) to determine which rights are granted or denied. 

 To request the same access rights as the existing token, specify zero. 

 To request all access rights that are valid for the caller, specify MAXIMUM_ALLOWED.</dd><dt>tokenAttributes</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">DevCase.Interop.Unmanaged.Win32.Structures.SecurityAttributes</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">SecurityAttributes</a> structure that specifies a security descriptor for the new token and determines whether child processes can inherit the token. 

 If *tokenAttributes* is NULL, the token gets a default security descriptor and the handle cannot be inherited. 

 If the security descriptor contains a system access control list (SACL), the token gets ACCESS_SYSTEM_SECURITY access right, even if it was not requested in *desiredAccess*. 

 To set the owner in the security descriptor for the new token, the caller's process token must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessPrivileges">RestorePrivilege</a> (SE_RESTORE_NAME) privilege set.</dd><dt>impersonationLevel</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SecurityImpersonationLevel">DevCase.Interop.Unmanaged.Win32.Enums.SecurityImpersonationLevel</a><br />The impersonation level of the new token.</dd><dt>tokenType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenType">DevCase.Interop.Unmanaged.Win32.Enums.TokenType</a><br />A values that differentiate between a primary token and an impersonation token.</dd><dt>refNewToken</dt><dd>Type: System.IntPtr<br />A pointer to a HANDLE variable that receives the new token. 

 When you have finished using the new token, call the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CloseHandle">CloseHandle(IntPtr)</a> function to close the token handle.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error(). 



## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/securitybaseapi/nf-securitybaseapi-duplicatetokenex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/securitybaseapi/nf-securitybaseapi-duplicatetokenex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />