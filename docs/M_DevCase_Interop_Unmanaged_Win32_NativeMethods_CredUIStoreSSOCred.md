# NativeMethods.CredUIStoreSSOCred Method 
 

Stores a single logon credential.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static Win32ErrorCode CredUIStoreSSOCred(
	string realm,
	string userName,
	string password,
	bool persist
)
```

**VB**<br />
``` VB
<DllImportAttribute("CredUI.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function CredUIStoreSSOCred ( 
	realm As String,
	userName As String,
	password As String,
	persist As Boolean
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim realm As String
Dim userName As String
Dim password As String
Dim persist As Boolean
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.CredUIStoreSSOCred(realm, 
	userName, password, persist)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"CredUI.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static Win32ErrorCode CredUIStoreSSOCred(
	String^ realm, 
	String^ userName, 
	String^ password, 
	bool persist
)
```

**F#**<br />
``` F#
[<DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member CredUIStoreSSOCred : 
        realm : string * 
        userName : string * 
        password : string * 
        persist : bool -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>realm</dt><dd>Type: System.String<br />Pointer to a null-terminated string that specifies the realm. 

 If this parameter is NULL, the default realm is used.</dd><dt>userName</dt><dd>Type: System.String<br />Pointer to a null-terminated string that specifies the user's name.</dd><dt>password</dt><dd>Type: System.String<br />Pointer to a null-terminated string that specifies the user's password. 

 When you have finished using the password, clear the password from memory by calling the `SecureZeroMemory` function.</dd><dt>persist</dt><dd>Type: System.Boolean<br />Boolean value that specifies whether the credentials are persisted. 

 If this value is `true` (`True` in Visual Basic), the credentials are persisted. 

 If this value is `false` (`False` in Visual Basic), the credentials are not persisted.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a> on success, or a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduistoressocredw" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduistoressocredw</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />