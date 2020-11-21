# CredentialsDialogOptions Enumeration
 

Flags for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUIPromptForCredentials">CredUIPromptForCredentials(CredUiInfo, String, IntPtr, Win32ErrorCode, StringBuilder, Int32, StringBuilder, Int32, Boolean, CredentialsDialogOptions)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUICmdLinePromptForCredentials">CredUICmdLinePromptForCredentials(String, IntPtr, Win32ErrorCode, StringBuilder, UInt32, StringBuilder, UInt32, Boolean, CredentialsDialogOptions)</a> functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum CredentialsDialogOptions
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration CredentialsDialogOptions
```

**VB Usage**<br />
``` VB Usage
Dim instance As CredentialsDialogOptions
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class CredentialsDialogOptions
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type CredentialsDialogOptions
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.Default">**Default**</td><td>393344</td><td>Default behavior.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.None">**None**</td><td>0</td><td>None.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.IncorrectPassword">**IncorrectPassword**</td><td>1</td><td>Silently ignore this flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.DoNotPersist">**DoNotPersist**</td><td>2</td><td>Do not display the save message or store credentials. ShowSaveCheckBox can also be passed to display the save message only and return the result In `refSave` parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.RequestAdministrator">**RequestAdministrator**</td><td>4</td><td>Silently ignore this flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.ExcludeCertificates">**ExcludeCertificates**</td><td>8</td><td>Prompt for user name/password. 

 If the pszUserName parameter is specified, the user name is omitted. 

 If the credential is persisted, store the passed-in user name with the credential.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.RequireCertificate">**RequireCertificate**</td><td>16</td><td>Reserved for future use; do not pass this flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.ShowSaveCheckBox">**ShowSaveCheckBox**</td><td>64</td><td>Display the save message and return `Tre` in the `refSave` parameter if the user answers "y" (Yes), `false` (`False` in Visual Basic) if the user answers "n" (No). 

DoNotPersist must be specified to use this flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.AlwaysShowUI">**AlwaysShowUI**</td><td>128</td><td>Display a user interface if the credentials can be returned from an existing credential in credential manager. 

 This flag is permitted only if GenericCredentials is also specified and is used only in conjunction with GenericCredentials.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.RequireSmartCard">**RequireSmartCard**</td><td>256</td><td>Use a smart card and prompt for a PIN. 

 If more than one smart card is available, select one of them. 

 If the `userName` parameter passes a string that is not empty, the string must match the UPN associated with the certificate on one of the smart cards. 

 A UPN matches if the string matches the whole UPN on the certificate or the string matches the part to the left of the at sign (@) in the UPN of the certificate. 

 If there is a match, the matching smart card is selected.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.PasswordOnlyOk">**PasswordOnlyOk**</td><td>512</td><td>Populate the combo box with the password only. Do not allow a user name to be entered.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.ValidateUsername">**ValidateUsername**</td><td>1024</td><td>Check that the user name is valid.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.CompleteUsername">**CompleteUsername**</td><td>2048</td><td>Populate the combo box with the prompt for a user name.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.Persist">**Persist**</td><td>4096</td><td>Do not show the save message, but save the credential as though the user answered "y" (Yes).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.ServerCredential">**ServerCredential**</td><td>16384</td><td>This flag is meaningful only in locating a matching credential to prefill the dialog box, should authentication fail. 

 When this flag is specified, wildcard credentials will not be matched. 

 It has no effect when writing a credential. 

 CredUI does not create credentials that contain wildcard characters. 

 Any found were either created explicitly by the user or created programmatically, as happens when a RAS connection is made.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.ExpectConfirmation">**ExpectConfirmation**</td><td>131072</td><td>Specifies that the caller will call CredUIConfirmCredentials to determine whether the returned credentials are actually valid. 

 This ensures that credentials that are not valid are not saved to the credential manager. 

 Specify this flag unless DoNotPersist is specified.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.GenericCredentials">**GenericCredentials**</td><td>262144</td><td>Consider the credentials entered by the user a generic credential.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.UsernameTargetCredentials">**UsernameTargetCredentials**</td><td>524288</td><td>The credential is a run-as credential. 

 The `targetName` parameter specifies the name of the command or program being run. 

 It is used for prompting purposes only.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions.KeepUsername">**KeepUsername**</td><td>1048576</td><td>Do not allow the user to change the supplied user name.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduipromptforcredentialsa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduipromptforcredentialsa</a><a href="https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduicmdlinepromptforcredentialsa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduicmdlinepromptforcredentialsa</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />