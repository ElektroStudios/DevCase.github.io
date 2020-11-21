# CredentialsPackFlags Enumeration
 

Specifies how a credential should be packed/unpacked when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredPackAuthenticationBuffer">CredPackAuthenticationBuffer(CredentialsPackFlags, String, String, IntPtr, Int32)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUnPackAuthenticationBuffer">CredUnPackAuthenticationBuffer(CredentialsPackFlags, IntPtr, Int32, IntPtr, Int32, IntPtr, Int32, IntPtr, Int32)</a> functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum CredentialsPackFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration CredentialsPackFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As CredentialsPackFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class CredentialsPackFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type CredentialsPackFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsPackFlags.ProtectedCredentials">**ProtectedCredentials**</td><td>1</td><td>Encrypts the credential so that it can only be decrypted by processes in the caller's logon session.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsPackFlags.WowBuffer">**WowBuffer**</td><td>2</td><td>Encrypts the credential in a WOW buffer.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsPackFlags.GenericCredentials">**GenericCredentials**</td><td>4</td><td>Encrypts the credential in a CRED_GENERIC buffer.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsPackFlags.IdProviderCredentials">**IdProviderCredentials**</td><td>8</td><td>Encrypts the credential of an online identity into a SEC_WINNT_AUTH_IDENTITY_EX2 structure. 

 If GenericCredentials and IdProviderCredentials are not set, encrypts the credentials in a KERB_INTERACTIVE_LOGON buffer.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-credpackauthenticationbuffera" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-credpackauthenticationbuffera</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />