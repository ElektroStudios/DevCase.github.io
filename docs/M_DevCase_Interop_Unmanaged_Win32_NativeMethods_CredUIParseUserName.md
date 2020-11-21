# NativeMethods.CredUIParseUserName Method 
 

Extracts the domain and user account name from a fully qualified user name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static Win32ErrorCode CredUIParseUserName(
	string userName,
	StringBuilder userBuffer,
	int userBufferSize,
	StringBuilder domainName,
	int domainNameSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("CredUI.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function CredUIParseUserName ( 
	userName As String,
	userBuffer As StringBuilder,
	userBufferSize As Integer,
	domainName As StringBuilder,
	domainNameSize As Integer
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim userName As String
Dim userBuffer As StringBuilder
Dim userBufferSize As Integer
Dim domainName As StringBuilder
Dim domainNameSize As Integer
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.CredUIParseUserName(userName, 
	userBuffer, userBufferSize, domainName, 
	domainNameSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"CredUI.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static Win32ErrorCode CredUIParseUserName(
	String^ userName, 
	StringBuilder^ userBuffer, 
	int userBufferSize, 
	StringBuilder^ domainName, 
	int domainNameSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member CredUIParseUserName : 
        userName : string * 
        userBuffer : StringBuilder * 
        userBufferSize : int * 
        domainName : StringBuilder * 
        domainNameSize : int -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>userName</dt><dd>Type: System.String<br />Pointer to a null-terminated string that contains the user name to be parsed. 

 The name must be in UPN or down-level format, or a certificate. 

 Typically, `userName` is received from the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUIPromptForCredentials">CredUIPromptForCredentials(CredUiInfo, String, IntPtr, Win32ErrorCode, StringBuilder, Int32, StringBuilder, Int32, Boolean, CredentialsDialogOptions)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CredUICmdLinePromptForCredentials">CredUICmdLinePromptForCredentials(String, IntPtr, Win32ErrorCode, StringBuilder, UInt32, StringBuilder, UInt32, Boolean, CredentialsDialogOptions)</a>.</dd><dt>userBuffer</dt><dd>Type: System.Text.StringBuilder<br />Pointer to a null-terminated string that receives the user account name.</dd><dt>userBufferSize</dt><dd>Type: System.Int32<br />Maximum number of characters to write to the pszUser string including the terminating null character.</dd><dt>domainName</dt><dd>Type: System.Text.StringBuilder<br />Pointer to a null-terminated string that receives the domain name. 

 If `userName` specifies a certificate, `domainName` will be NULL.</dd><dt>domainNameSize</dt><dd>Type: System.Int32<br />Maximum number of characters to write to the `domainName` string including the terminating null character.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a> on success, or a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduiparseusernamea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduiparseusernamea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />