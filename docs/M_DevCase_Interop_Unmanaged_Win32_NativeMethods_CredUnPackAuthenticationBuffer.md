# NativeMethods.CredUnPackAuthenticationBuffer Method (CredentialsPackFlags, IntPtr, Int32, IntPtr, Int32, IntPtr, Int32, IntPtr, Int32)
 

Converts an authentication buffer returned by a call to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUIPromptForWindowsCredentials">CredUIPromptForWindowsCredentials(CredUiInfo, Win32ErrorCode, UInt32, IntPtr, UInt32, IntPtr, UInt32, Boolean, WindowsCredentialsDialogOptions)</a> function into a string user name and password.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool CredUnPackAuthenticationBuffer(
	CredentialsPackFlags flags,
	IntPtr authBuffer,
	int authBufferSize,
	IntPtr userName,
	ref int refUserNameSize,
	IntPtr domainName,
	ref int refDomainNameSize,
	IntPtr password,
	ref int refPasswordSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("CredUI.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function CredUnPackAuthenticationBuffer ( 
	flags As CredentialsPackFlags,
	authBuffer As IntPtr,
	authBufferSize As Integer,
	userName As IntPtr,
	ByRef refUserNameSize As Integer,
	domainName As IntPtr,
	ByRef refDomainNameSize As Integer,
	password As IntPtr,
	ByRef refPasswordSize As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim flags As CredentialsPackFlags
Dim authBuffer As IntPtr
Dim authBufferSize As Integer
Dim userName As IntPtr
Dim refUserNameSize As Integer
Dim domainName As IntPtr
Dim refDomainNameSize As Integer
Dim password As IntPtr
Dim refPasswordSize As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.CredUnPackAuthenticationBuffer(flags, 
	authBuffer, authBufferSize, userName, 
	refUserNameSize, domainName, refDomainNameSize, 
	password, refPasswordSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"CredUI.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool CredUnPackAuthenticationBuffer(
	CredentialsPackFlags flags, 
	IntPtr authBuffer, 
	int authBufferSize, 
	IntPtr userName, 
	int% refUserNameSize, 
	IntPtr domainName, 
	int% refDomainNameSize, 
	IntPtr password, 
	int% refPasswordSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member CredUnPackAuthenticationBuffer : 
        flags : CredentialsPackFlags * 
        authBuffer : IntPtr * 
        authBufferSize : int * 
        userName : IntPtr * 
        refUserNameSize : int byref * 
        domainName : IntPtr * 
        refDomainNameSize : int byref * 
        password : IntPtr * 
        refPasswordSize : int byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsPackFlags">DevCase.Interop.Unmanaged.Win32.Enums.CredentialsPackFlags</a><br />Setting the value of this parameter to CRED_PACK_PROTECTED_CREDENTIALS specifies that the function attempts to decrypt the credentials in the authentication buffer. If the credential cannot be decrypted, the function returns `false` (`False` in Visual Basic), and a call to the GetLastError function will return the value <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_NOT_CAPABLE</a>. 

 How the decryption is done depends on the format of the authentication buffer. 

 If the authentication buffer is a SEC_WINNT_AUTH_IDENTITY_EX2 structure, the function can decrypt the buffer if it is encrypted by using SspiEncryptAuthIdentityEx with the SEC_WINNT_AUTH_IDENTITY_ENCRYPT_SAME_LOGON option. 

 If the authentication buffer is one of the marshaled KERB_*_LOGON structures, the function decrypts the password before returning it in the *password* buffer.</dd><dt>authBuffer</dt><dd>Type: System.IntPtr<br />A pointer to the authentication buffer to be converted. 

 This buffer is typically the output of the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUIPromptForWindowsCredentials">CredUIPromptForWindowsCredentials(CredUiInfo, Win32ErrorCode, UInt32, IntPtr, UInt32, IntPtr, UInt32, Boolean, WindowsCredentialsDialogOptions)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredPackAuthenticationBuffer">CredPackAuthenticationBuffer(CredentialsPackFlags, String, String, IntPtr, Int32)</a> function.</dd><dt>authBufferSize</dt><dd>Type: System.Int32<br />The size, in bytes, of the *authBuffer* buffer.</dd><dt>userName</dt><dd>Type: System.IntPtr<br />A pointer to a null-terminated string that receives the user name. 

 This string can be a marshaled credential.</dd><dt>refUserNameSize</dt><dd>Type: System.Int32<br />A pointer to a value that specifies the size, in characters, of the *userName* buffer. 

 On output, if the buffer is not of sufficient size, specifies the required size, in characters, of the *userName* buffer. The size includes terminating null character.</dd><dt>domainName</dt><dd>Type: System.IntPtr<br />A pointer to a null-terminated string that receives the name of the user's domain.</dd><dt>refDomainNameSize</dt><dd>Type: System.Int32<br />A pointer to a value that specifies the size, in characters, of the *domainName* buffer. 

 On output, if the buffer is not of sufficient size, specifies the required size, in characters, of the *domainName* buffer. The size includes the terminating null character. 

 The required size can be zero if there is no domain name.</dd><dt>password</dt><dd>Type: System.IntPtr<br />A pointer to a null-terminated string that receives the password.</dd><dt>refPasswordSize</dt><dd>Type: System.Int32<br />A pointer to a value that specifies the size, in characters, of the *password* buffer. On output, if the buffer is not of sufficient size, specifies the required size, in characters, of the *password* buffer. The size includes the terminating null character. This string can be a marshaled credential.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeds; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-credunpackauthenticationbuffera" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-credunpackauthenticationbuffera</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUnPackAuthenticationBuffer">CredUnPackAuthenticationBuffer Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />