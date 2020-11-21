# NativeMethods.CredUIPromptForCredentials Method 
 

Creates and displays a configurable dialog box that accepts credentials information from a user.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static Win32ErrorCode CredUIPromptForCredentials(
	ref CredUiInfo refUiInfo,
	string targetName,
	[OptionalAttribute] IntPtr reserved,
	Win32ErrorCode authError,
	StringBuilder userName,
	int userNameSize,
	StringBuilder password,
	int passwordSize,
	ref bool refSave,
	CredentialsDialogOptions flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("CredUI.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function CredUIPromptForCredentials ( 
	ByRef refUiInfo As CredUiInfo,
	targetName As String,
	<OptionalAttribute> reserved As IntPtr,
	authError As Win32ErrorCode,
	userName As StringBuilder,
	userNameSize As Integer,
	password As StringBuilder,
	passwordSize As Integer,
	ByRef refSave As Boolean,
	flags As CredentialsDialogOptions
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim refUiInfo As CredUiInfo
Dim targetName As String
Dim reserved As IntPtr
Dim authError As Win32ErrorCode
Dim userName As StringBuilder
Dim userNameSize As Integer
Dim password As StringBuilder
Dim passwordSize As Integer
Dim refSave As Boolean
Dim flags As CredentialsDialogOptions
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.CredUIPromptForCredentials(refUiInfo, 
	targetName, reserved, authError, 
	userName, userNameSize, password, 
	passwordSize, refSave, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"CredUI.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static Win32ErrorCode CredUIPromptForCredentials(
	CredUiInfo% refUiInfo, 
	String^ targetName, 
	[OptionalAttribute] IntPtr reserved, 
	Win32ErrorCode authError, 
	StringBuilder^ userName, 
	int userNameSize, 
	StringBuilder^ password, 
	int passwordSize, 
	bool% refSave, 
	CredentialsDialogOptions flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member CredUIPromptForCredentials : 
        refUiInfo : CredUiInfo byref * 
        targetName : string * 
        [<OptionalAttribute>] reserved : IntPtr * 
        authError : Win32ErrorCode * 
        userName : StringBuilder * 
        userNameSize : int * 
        password : StringBuilder * 
        passwordSize : int * 
        refSave : bool byref * 
        flags : CredentialsDialogOptions -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>refUiInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_CredUiInfo">DevCase.Interop.Unmanaged.Win32.Structures.CredUiInfo</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_CredUiInfo">CredUiInfo</a> structure that contains information for customizing the appearance of the dialog box. 

 If the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_CredUiInfo_Parent">Parent</a> member is not Zero, this function displays a modal dialog box centered on the parent window. 

 If the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_CredUiInfo_Parent">Parent</a> member is Zero, the function displays a dialog box centered on the screen.</dd><dt>targetName</dt><dd>Type: System.String<br />A pointer to a null-terminated string that contains the name of the target for the credentials, typically a server name. 

 For Distributed File System (DFS) connections, this string is of the form `ServerName/ShareName`. 

 This parameter is used to identify target information when storing and retrieving credentials.</dd><dt>reserved (Optional)</dt><dd>Type: System.IntPtr<br />This parameter is reserved for future use. It must be Zero.</dd><dt>authError</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">DevCase.Interop.Unmanaged.Win32.Enums.Win32ErrorCode</a><br />Specifies why the credential dialog box is needed. 

 A caller can pass this Windows error parameter, returned by another authentication call, to allow the dialog box to accommodate certain errors. 

 For example, if the password expired status code is passed, the dialog box could prompt the user to change the password on the account.</dd><dt>userName</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a null-terminated string that contains the user name for the credentials. 

 If a nonzero-length string is passed, the UserName option of the dialog box is prefilled with the string. 

 In the case of credentials other than UserName/Password, a marshaled format of the credential can be passed in. This string is created by calling CredMarshalCredential function. 

 This function copies the user-supplied name to this buffer, copying a maximum of *userNameSize* characters. This format can be converted to UserName/Password format by using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUIParseUserName">CredUIParseUserName(String, StringBuilder, Int32, StringBuilder, Int32)</a>. 

 A marshaled format can be passed directly to a security support provider (SSP). 

 If the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">DoNotPersist</a> flag is not specified, the value returned in this parameter is of a form that should not be inspected, printed, or persisted other than passing it to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUIParseUserName">CredUIParseUserName(String, StringBuilder, Int32, StringBuilder, Int32)</a>. 

 The subsequent results of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUIParseUserName">CredUIParseUserName(String, StringBuilder, Int32, StringBuilder, Int32)</a> can be passed only to a client-side authentication function such as WNetAddConnection or an SSP function. 

 If no domain or server is specified as part of this parameter, the value of the *targetName* parameter is used as the domain to form a `DomainName/UserName` pair. 

 On output, this parameter receives a string that contains that `DomainName/UserName` pair.</dd><dt>userNameSize</dt><dd>Type: System.Int32<br />The maximum number of characters that can be copied to *userName* including the terminating null character.</dd><dt>password</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a null-terminated string that contains the password for the credentials. 

 If a nonzero-length string is specified for *password*, the password option of the dialog box will be prefilled with the string. 

 This function copies the user-supplied password to this buffer, copying a maximum of *passwordSize* characters. 

 If the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">DoNotPersist</a> flag is not specified, the value returned in this parameter is of a form that should not be inspected, printed, or persisted other than passing it to a client-side authentication function such as WNetAddConnection or an SSP function. 

 When you have finished using the password, clear the password from memory by calling the `SecureZeroMemory` function.</dd><dt>passwordSize</dt><dd>Type: System.Int32<br />The maximum number of characters that can be copied to *password* including the terminating null character.</dd><dt>refSave</dt><dd>Type: System.Boolean<br />A value that specifies the initial state of the Save check box and receives the state of the Save check box after the user has responded to the dialog box. 

 If this value is not NULL and CredUIPromptForCredentials(CredUiInfo, String, IntPtr, Win32ErrorCode, StringBuilder, Int32, StringBuilder, Int32, Boolean, CredentialsDialogOptions) returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>, then *refSave* returns the state of the Save check box when the user chose OK in the dialog box. 

 If the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">Persist</a> flag is specified, the Save check box is not displayed, but is considered to be selected. 

 If the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">DoNotPersist</a> flag is specified and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">ShowSaveCheckBox</a> is not specified, the Save check box is not displayed, but is considered to be cleared. 

 An application that needs to use CredUI to prompt the user for credentials, but does not need the credential management services provided by the credential manager, can use *refSave* to receive the state of the Save check box after the user closes the dialog box. To do this, the caller must specify <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">DoNotPersist</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">ShowSaveCheckBox</a> in *flags*. 

 When <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">DoNotPersist</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">ShowSaveCheckBox</a> are set, the application is responsible for examining *pfSave after the function returns, and if *refSave* is `true` (`True` in Visual Basic), then the application must take the appropriate action to save the user credentials within the resources of the application.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions</a><br />A value that specifies special behavior for this function.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a> on success, or a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduipromptforcredentialsa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduipromptforcredentialsa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />