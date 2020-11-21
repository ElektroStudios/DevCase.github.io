# WindowsCredentialsDialogOptions Enumeration
 

Flags for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUIPromptForWindowsCredentials">CredUIPromptForWindowsCredentials(CredUiInfo, Win32ErrorCode, UInt32, IntPtr, UInt32, IntPtr, UInt32, Boolean, WindowsCredentialsDialogOptions)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum WindowsCredentialsDialogOptions
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration WindowsCredentialsDialogOptions
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowsCredentialsDialogOptions
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class WindowsCredentialsDialogOptions
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type WindowsCredentialsDialogOptions
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowsCredentialsDialogOptions.None">**None**</td><td>0</td><td>None.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowsCredentialsDialogOptions.Generic">**Generic**</td><td>1</td><td>The caller is requesting that the credential provider return the user name and password in plain text. 

 This value cannot be combined with SecurePrompt.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowsCredentialsDialogOptions.CheckBox">**CheckBox**</td><td>2</td><td>The Save check box is displayed in the dialog box.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowsCredentialsDialogOptions.AuthPackageOnly">**AuthPackageOnly**</td><td>16</td><td>Only credential providers that support the authentication package specified by the `refAuthPackage` parameter should be enumerated. 

 This value cannot be combined with InCredentialOnly.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowsCredentialsDialogOptions.InCredentialOnly">**InCredentialOnly**</td><td>32</td><td>Only the credentials specified by the `inAuthBuffer` parameter for the authentication package specified by the `refAuthPackage` parameter should be enumerated. 

 If this flag is set, and the `inAuthBuffer` parameter is Zero, the function fails. 

 This value cannot be combined with AuthPackageOnly.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowsCredentialsDialogOptions.EnumerateAdmins">**EnumerateAdmins**</td><td>256</td><td>Credential providers should enumerate only administrators. 

 This value is intended for User Account Control (UAC) purposes only. 

 We recommend that external callers not set this flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowsCredentialsDialogOptions.EnumerateCurrentUser">**EnumerateCurrentUser**</td><td>512</td><td>Only the incoming credentials for the authentication package specified by the `refAuthPackage` parameter should be enumerated.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowsCredentialsDialogOptions.SecurePrompt">**SecurePrompt**</td><td>4096</td><td>The credential dialog box should be displayed on the secure desktop. 

 This value cannot be combined with Generic.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowsCredentialsDialogOptions.PrePrompting">**PrePrompting**</td><td>8192</td><td>The credential dialog box is invoked by the SspiPromptForCredentials function, and the client is prompted before a prior handshake. 

 If SSPIPFC_NO_CHECKBOX is passed in the `inAuthBuffer` parameter, then the credential provider should not display the check box.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowsCredentialsDialogOptions.Pack32Wow">**Pack32Wow**</td><td>268435456</td><td>The credential provider should align the credential BLOB pointed to by the `refOutAuthBuffer` parameter to a 32-bit boundary, even if the provider is running on a 64-bit system.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduipromptforwindowscredentialsa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduipromptforwindowscredentialsa</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />