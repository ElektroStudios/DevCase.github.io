# NativeMethods.CredUIConfirmCredentials Method 
 

The CredUIConfirmCredentials(String, Boolean) function is called after <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUIPromptForCredentials">CredUIPromptForCredentials(CredUiInfo, String, IntPtr, Win32ErrorCode, StringBuilder, Int32, StringBuilder, Int32, Boolean, CredentialsDialogOptions)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUICmdLinePromptForCredentials">CredUICmdLinePromptForCredentials(String, IntPtr, Win32ErrorCode, StringBuilder, UInt32, StringBuilder, UInt32, Boolean, CredentialsDialogOptions)</a>, to confirm the validity of the credential harvested. 

CredUIConfirmCredentials(String, Boolean) must be called if the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CredentialsDialogOptions">ExpectConfirmation</a> flag was passed to the "prompt" function, either <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUIPromptForCredentials">CredUIPromptForCredentials(CredUiInfo, String, IntPtr, Win32ErrorCode, StringBuilder, Int32, StringBuilder, Int32, Boolean, CredentialsDialogOptions)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUICmdLinePromptForCredentials">CredUICmdLinePromptForCredentials(String, IntPtr, Win32ErrorCode, StringBuilder, UInt32, StringBuilder, UInt32, Boolean, CredentialsDialogOptions)</a>, and the "prompt" function returned <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. 

 After calling the "prompt" function and before calling CredUIConfirmCredentials(String, Boolean), the caller must determine whether the credentials are actually valid by using the credentials to access the resource specified by *targetName*. The results of that validation test are passed to CredUIConfirmCredentials(String, Boolean) in the *confirm* parameter.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static Win32ErrorCode CredUIConfirmCredentials(
	string targetName,
	bool confirm
)
```

**VB**<br />
``` VB
<DllImportAttribute("CredUI.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function CredUIConfirmCredentials ( 
	targetName As String,
	confirm As Boolean
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim targetName As String
Dim confirm As Boolean
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.CredUIConfirmCredentials(targetName, 
	confirm)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"CredUI.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static Win32ErrorCode CredUIConfirmCredentials(
	String^ targetName, 
	bool confirm
)
```

**F#**<br />
``` F#
[<DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member CredUIConfirmCredentials : 
        targetName : string * 
        confirm : bool -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>targetName</dt><dd>Type: System.String<br />Pointer to a null-terminated string that contains the name of the target for the credentials, typically a domain or server application name. 

 This must be the same value passed as *targetName* to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUIPromptForCredentials">CredUIPromptForCredentials(CredUiInfo, String, IntPtr, Win32ErrorCode, StringBuilder, Int32, StringBuilder, Int32, Boolean, CredentialsDialogOptions)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUICmdLinePromptForCredentials">CredUICmdLinePromptForCredentials(String, IntPtr, Win32ErrorCode, StringBuilder, UInt32, StringBuilder, UInt32, Boolean, CredentialsDialogOptions)</a>.</dd><dt>confirm</dt><dd>Type: System.Boolean<br />Specifies whether the credentials returned from the prompt function are valid. 

 If `true` (`True` in Visual Basic), the credentials are stored in the credential manager as defined by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUIPromptForCredentials">CredUIPromptForCredentials(CredUiInfo, String, IntPtr, Win32ErrorCode, StringBuilder, Int32, StringBuilder, Int32, Boolean, CredentialsDialogOptions)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUICmdLinePromptForCredentials">CredUICmdLinePromptForCredentials(String, IntPtr, Win32ErrorCode, StringBuilder, UInt32, StringBuilder, UInt32, Boolean, CredentialsDialogOptions)</a>. 

 If `false` (`False` in Visual Basic), the credentials are not stored and various pieces of memory are cleaned up.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />Status of the operation is returned. 

 The caller can check this status to determine whether the credential confirm operation succeeded. 

 Most applications ignore this status code because the application's connection to the resource has already been done. The operation can fail because the credential was not found on the list of credentials awaiting confirmation, or because the attempt to write or delete the credential failed. 

 Failure to find the credential on the list can occur because the credential was never queued or as a result of too many credentials being queued. 

 Up to five credentials can be queued before older ones are discarded as newer ones are queued.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduiconfirmcredentialsa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduiconfirmcredentialsa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />