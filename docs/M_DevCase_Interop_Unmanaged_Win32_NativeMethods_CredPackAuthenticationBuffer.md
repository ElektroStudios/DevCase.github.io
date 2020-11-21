# NativeMethods.CredPackAuthenticationBuffer Method 
 

Converts a string user name and password into an authentication buffer. 

 Beginning with Windows 8, the CredPackAuthenticationBuffer(CredentialsPackFlags, String, String, IntPtr, Int32) function converts an identity credential into an authentication buffer, which is a SEC_WINNT_AUTH_IDENTITY_EX2 structure. This buffer can be passed to LsaLogonUser, AcquireCredentialsHandle, or other identity provider interfaces.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool CredPackAuthenticationBuffer(
	CredentialsPackFlags flags,
	string userName,
	string password,
	IntPtr packedCredentials,
	ref int refPackedCredentialsSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("CredUI.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function CredPackAuthenticationBuffer ( 
	flags As CredentialsPackFlags,
	userName As String,
	password As String,
	packedCredentials As IntPtr,
	ByRef refPackedCredentialsSize As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim flags As CredentialsPackFlags
Dim userName As String
Dim password As String
Dim packedCredentials As IntPtr
Dim refPackedCredentialsSize As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.CredPackAuthenticationBuffer(flags, 
	userName, password, packedCredentials, 
	refPackedCredentialsSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"CredUI.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool CredPackAuthenticationBuffer(
	CredentialsPackFlags flags, 
	String^ userName, 
	String^ password, 
	IntPtr packedCredentials, 
	int% refPackedCredentialsSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member CredPackAuthenticationBuffer : 
        flags : CredentialsPackFlags * 
        userName : string * 
        password : string * 
        packedCredentials : IntPtr * 
        refPackedCredentialsSize : int byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsPackFlags">DevCase.Interop.Unmanaged.Win32.Enums.CredentialsPackFlags</a><br />Specifies how the credential should be packed.</dd><dt>userName</dt><dd>Type: System.String<br />A pointer to a null-terminated string that specifies the user name to be converted. 

 For domain users, the string must be in the following format: 

`DomainName/UserName`</dd><dt>password</dt><dd>Type: System.String<br />A pointer to a null-terminated string that specifies the password to be converted.</dd><dt>packedCredentials</dt><dd>Type: System.IntPtr<br />A pointer to an array of bytes that, on output, receives the packed authentication buffer. 

 This parameter can be NULL to receive the required buffer size in the *refPackedCredentialsSize* parameter.</dd><dt>refPackedCredentialsSize</dt><dd>Type: System.Int32<br />A value that specifies the size, in bytes, of the *packedCredentials* buffer. 

 On output, if the buffer is not of sufficient size, specifies the required size, in bytes, of the *packedCredentials* buffer.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeds; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-credpackauthenticationbuffera" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-credpackauthenticationbuffera</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />