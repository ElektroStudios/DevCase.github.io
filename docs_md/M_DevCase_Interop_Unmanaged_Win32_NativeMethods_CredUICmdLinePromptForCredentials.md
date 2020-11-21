# NativeMethods.CredUICmdLinePromptForCredentials Method 
 

prompts for and accepts credential information from a user working in a command-line (console) application. 

 The name and password typed by the user are passed back to the calling application for verification.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static Win32ErrorCode CredUICmdLinePromptForCredentials(
	[OptionalAttribute] string targetName,
	[OptionalAttribute] IntPtr reserved,
	Win32ErrorCode authError,
	StringBuilder userName,
	uint userNameSize,
	StringBuilder password,
	uint passwordSize,
	ref bool refSave,
	CredentialsDialogOptions flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("CredUI.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function CredUICmdLinePromptForCredentials ( 
	<OptionalAttribute> targetName As String,
	<OptionalAttribute> reserved As IntPtr,
	authError As Win32ErrorCode,
	userName As StringBuilder,
	userNameSize As UInteger,
	password As StringBuilder,
	passwordSize As UInteger,
	ByRef refSave As Boolean,
	flags As CredentialsDialogOptions
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim targetName As String
Dim reserved As IntPtr
Dim authError As Win32ErrorCode
Dim userName As StringBuilder
Dim userNameSize As UInteger
Dim password As StringBuilder
Dim passwordSize As UInteger
Dim refSave As Boolean
Dim flags As CredentialsDialogOptions
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.CredUICmdLinePromptForCredentials(targetName, 
	reserved, authError, userName, userNameSize, 
	password, passwordSize, refSave, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"CredUI.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static Win32ErrorCode CredUICmdLinePromptForCredentials(
	[OptionalAttribute] [InAttribute] String^ targetName, 
	[OptionalAttribute] IntPtr reserved, 
	Win32ErrorCode authError, 
	StringBuilder^ userName, 
	unsigned int userNameSize, 
	StringBuilder^ password, 
	unsigned int passwordSize, 
	bool% refSave, 
	CredentialsDialogOptions flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member CredUICmdLinePromptForCredentials : 
        [<OptionalAttribute>] targetName : string * 
        [<OptionalAttribute>] reserved : IntPtr * 
        authError : Win32ErrorCode * 
        userName : StringBuilder * 
        userNameSize : uint32 * 
        password : StringBuilder * 
        passwordSize : uint32 * 
        refSave : bool byref * 
        flags : CredentialsDialogOptions -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>targetName (Optional)</dt><dd>Type: System.String<br />A pointer to a null-terminated string that contains the name of the target for the credentials, 

 typically a server name. For DFS connections, this string is of the form `ServerName/ShareName`. 

 The *targetName* parameter is used to identify the target information and is used to store and retrieve the credential.</dd><dt>reserved (Optional)</dt><dd>Type: System.IntPtr<br />Currently reserved and must be Zero.</dd><dt>authError</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">DevCase.Interop.Unmanaged.Win32.Enums.Win32ErrorCode</a><br />Specifies why prompting for credentials is needed. 

 A caller can pass this Windows error parameter, returned by another authentication call, to allow the dialog box to accommodate certain errors. 

 For example, if the password expired status code is passed, the dialog box prompts the user to change the password on the account.</dd><dt>userName</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a null-terminated string that contains the credential user name. 

 If a nonzero-length string is specified for *userName*, the user will be prompted only for the password. 

 In the case of credentials other than username/password, a marshaled format of the credential can be passed in. This string is created by calling CredMarshalCredential function. 

 This function writes the user-supplied name to this buffer, copying a maximum of *userNameSize* characters. The string in this format can be converted to the user name/password format by calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUIParseUserName">CredUIParseUserName(String, StringBuilder, Int32, StringBuilder, Int32)</a> function. The string in its marshaled format can be passed directly to a security support provider (SSP). 

 If the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">DoNotPersist</a> flag is not specified, the value returned in this parameter is of a form that should not be inspected, printed, or persisted other than passing it to CredUIParseUsername. 

 The subsequent results of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUIParseUserName">CredUIParseUserName(String, StringBuilder, Int32, StringBuilder, Int32)</a> can be passed only to a client-side authentication API such as WNetAddConnection or the SSP API.</dd><dt>userNameSize</dt><dd>Type: System.UInt32<br />The maximum number of characters that can be copied to *userName* including the terminating null character.</dd><dt>password</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a null-terminated string that contains the password for the credentials. 

 If a nonzero-length string is specified for *password*, the password parameter will be prefilled with the string. 

 This function writes the user-supplied password to this buffer, copying a maximum of *passwordSize* characters. 

 If the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">DoNotPersist</a> flag is not specified, the value returned in this parameter is of a form that should not be inspected, printed, or persisted other than passing it to a client-side authentication function such as WNetAddConnection or an SSP function. 

 When you have finished using the password, clear the password from memory by calling the `SecureZeroMemory` function.</dd><dt>passwordSize</dt><dd>Type: System.UInt32<br />The maximum number of characters that can be copied to *password* including the terminating null character.</dd><dt>refSave</dt><dd>Type: System.Boolean<br />A value that specifies the initial state of the Save message and receives the state of the Save message after the user has responded to the command prompt. 

 If *refSave* is not NULL and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUIPromptForCredentials">CredUIPromptForCredentials(CredUiInfo, String, IntPtr, Win32ErrorCode, StringBuilder, Int32, StringBuilder, Int32, Boolean, CredentialsDialogOptions)</a> returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>, *refSave* returns the state of the Save message. 

 If the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">Persist</a> flag is specified, the Save message is not displayed but is considered to be "y" (Yes). 

 If the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">DoNotPersist</a> flag is specified and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">ShowSaveCheckBox</a> is not specified, the Save message is not displayed but is considered to be "n" (No).</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions</a><br />A value that specifies special behavior for this function.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a> on success, or a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduicmdlinepromptforcredentialsa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduicmdlinepromptforcredentialsa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />