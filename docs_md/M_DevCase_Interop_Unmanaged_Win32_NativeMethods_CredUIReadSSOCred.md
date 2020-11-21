# NativeMethods.CredUIReadSSOCred Method 
 

Retrieves the user name for a single logon credential

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static Win32ErrorCode CredUIReadSSOCred(
	string realm,
	out string refUserName
)
```

**VB**<br />
``` VB
<DllImportAttribute("CredUI.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function CredUIReadSSOCred ( 
	realm As String,
	<OutAttribute> ByRef refUserName As String
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim realm As String
Dim refUserName As String
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.CredUIReadSSOCred(realm, 
	refUserName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"CredUI.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static Win32ErrorCode CredUIReadSSOCred(
	String^ realm, 
	[OutAttribute] String^% refUserName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("CredUI.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member CredUIReadSSOCred : 
        realm : string * 
        refUserName : string byref -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>realm</dt><dd>Type: System.String<br />Pointer to a null-terminated string that specifies the realm. 

 If this parameter is NULL, the default realm is used.</dd><dt>refUserName</dt><dd>Type: System.String<br />Pointer to a pointer to a null-terminated string. When you have finished using the string, free *refUserName* by calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LocalFree">LocalFree(IntPtr)</a> function.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a> on success, or a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduireadssocredw" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wincred/nf-wincred-creduireadssocredw</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />