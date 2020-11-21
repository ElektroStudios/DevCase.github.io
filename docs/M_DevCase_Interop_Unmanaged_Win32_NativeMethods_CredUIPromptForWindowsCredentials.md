# NativeMethods.CredUIPromptForWindowsCredentials Method 
 

Creates and displays a configurable dialog box that allows users to supply credential information by using any credential provider installed on the local computer

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static Win32ErrorCode CredUIPromptForWindowsCredentials(
	ref CredUiInfo refiInfo,
	Win32ErrorCode authError,
	ref uint refAuthPackage,
	IntPtr inAuthBuffer,
	uint inAuthBufferSize,
	out IntPtr refOutAuthBuffer,
	out uint refOutAuthBufferSize,
	ref bool refSave,
	WindowsCredentialsDialogOptions flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("CredUI.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function CredUIPromptForWindowsCredentials ( 
	ByRef refiInfo As CredUiInfo,
	authError As Win32ErrorCode,
	ByRef refAuthPackage As UInteger,
	inAuthBuffer As IntPtr,
	inAuthBufferSize As UInteger,
	<OutAttribute> ByRef refOutAuthBuffer As IntPtr,
	<OutAttribute> ByRef refOutAuthBufferSize As UInteger,
	ByRef refSave As Boolean,
	flags As WindowsCredentialsDialogOptions
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim refiInfo As CredUiInfo
Dim authError As Win32ErrorCode
Dim refAuthPackage As UInteger
Dim inAuthBuffer As IntPtr
Dim inAuthBufferSize As UInteger
Dim refOutAuthBuffer As IntPtr
Dim refOutAuthBufferSize As UInteger
Dim refSave As Boolean
Dim flags As WindowsCredentialsDialogOptions
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.CredUIPromptForWindowsCredentials(refiInfo, 
	authError, refAuthPackage, inAuthBuffer, 
	inAuthBufferSize, refOutAuthBuffer, 
	refOutAuthBufferSize, refSave, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"CredUI.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static Win32ErrorCode CredUIPromptForWindowsCredentials(
	CredUiInfo% refiInfo, 
	Win32ErrorCode authError, 
	unsigned int% refAuthPackage, 
	IntPtr inAuthBuffer, 
	unsigned int inAuthBufferSize, 
	[OutAttribute] IntPtr% refOutAuthBuffer, 
	[OutAttribute] unsigned int% refOutAuthBufferSize, 
	bool% refSave, 
	WindowsCredentialsDialogOptions flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member CredUIPromptForWindowsCredentials : 
        refiInfo : CredUiInfo byref * 
        authError : Win32ErrorCode * 
        refAuthPackage : uint32 byref * 
        inAuthBuffer : IntPtr * 
        inAuthBufferSize : uint32 * 
        refOutAuthBuffer : IntPtr byref * 
        refOutAuthBufferSize : uint32 byref * 
        refSave : bool byref * 
        flags : WindowsCredentialsDialogOptions -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>refiInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_CredUiInfo">DevCase.Interop.Unmanaged.Win32.Structures.CredUiInfo</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_CredUiInfo">CredUiInfo</a> structure that contains information for customizing the appearance of the dialog box. 

 If the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_CredUiInfo_Parent">Parent</a> member is not Zero, this function displays a modal dialog box centered on the parent window. 

 If the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_CredUiInfo_Parent">Parent</a> member is Zero, the function displays a dialog box centered on the screen. 

 This function ignores the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_CredUiInfo_Banner">Banner</a> member.</dd><dt>authError</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">DevCase.Interop.Unmanaged.Win32.Enums.Win32ErrorCode</a><br />A Windows error code that is displayed in the dialog box. 

 If credentials previously collected were not valid, the caller uses this parameter to pass the error message from the API that collected the credentials (for example, Winlogon) to this function. 

 The corresponding error message is formatted and displayed in the dialog box. 

 Set the value of this parameter to zero to display no error message.</dd><dt>refAuthPackage</dt><dd>Type: System.UInt32<br />On input, the value of this parameter is used to specify the authentication package for which the credentials in the pvInAuthBuffer buffer are serialized. 

 If the value of *inAuthBuffer* is NULL and the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowsCredentialsDialogOptions">AuthPackageOnly</a> flag is set in the *flags* parameter, only credential providers capable of serializing credentials for the specified authentication package are to be enumerated. 

 To get the appropriate value to use for this parameter on input, call the LsaLookupAuthenticationPackage function and use the value of the AuthenticationPackage parameter of that function. 

 On output, this parameter specifies the authentication package for which the credentials in the *refOutAuthBuffer* buffer are serialized.</dd><dt>inAuthBuffer</dt><dd>Type: System.IntPtr<br />A pointer to a credential BLOB that is used to populate the credential fields in the dialog box. 

 Set the value of this parameter to NULL to leave the credential fields empty.</dd><dt>inAuthBufferSize</dt><dd>Type: System.UInt32<br />The size, in bytes, of the *inAuthBuffer* buffer.</dd><dt>refOutAuthBuffer</dt><dd>Type: System.IntPtr<br />The address of a pointer that, on output, specifies the credential BLOB. 

 For Kerberos, NTLM, or Negotiate credentials, call the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUnPackAuthenticationBuffer">CredUnPackAuthenticationBuffer(CredentialsPackFlags, IntPtr, Int32, IntPtr, Int32, IntPtr, Int32, IntPtr, Int32)</a> function to convert this BLOB to string representations of the credentials. 

 When you have finished using the credential BLOB, clear it from memory by calling the `SecureZeroMemory` function, and free it by calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CoTaskMemFree">CoTaskMemFree(IntPtr)</a> function.</dd><dt>refOutAuthBufferSize</dt><dd>Type: System.UInt32<br />The size, in bytes, of the *refOutAuthBuffer* buffer.</dd><dt>refSave</dt><dd>Type: System.Boolean<br />A pointer to a Boolean value that, on input, specifies whether the Save check box is selected in the dialog box that this function displays. 

 On output, the value of this parameter specifies whether the Save check box was selected when the user clicks the Submit button in the dialog box. 

 Set this parameter to NULL to ignore the Save check box.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowsCredentialsDialogOptions">DevCase.Interop.Unmanaged.Win32.Enums.WindowsCredentialsDialogOptions</a><br />A value that specifies behavior for this function.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If the function succeeds, the function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. If the function is canceled by the user, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_CANCELLED</a>. Any other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> value indicates that the function failed to load.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduipromptforwindowscredentialsa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduipromptforwindowscredentialsa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />