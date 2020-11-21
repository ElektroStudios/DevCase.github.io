# NativeMethods.InternetSetCookieEx Method 
 

Creates a cookie with a specified name that is associated with a specified URL. 

 This function differs from the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_InternetSetCookie">InternetSetCookie(String, String, String)</a> function by being able to create third-party cookies

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("WinINet.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static int InternetSetCookieEx(
	string urlName,
	string cookieName,
	string cookieData,
	int flags,
	IntPtr reserved
)
```

**VB**<br />
``` VB
<DllImportAttribute("WinINet.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function InternetSetCookieEx ( 
	urlName As String,
	cookieName As String,
	cookieData As String,
	flags As Integer,
	reserved As IntPtr
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim urlName As String
Dim cookieName As String
Dim cookieData As String
Dim flags As Integer
Dim reserved As IntPtr
Dim returnValue As Integer

returnValue = NativeMethods.InternetSetCookieEx(urlName, 
	cookieName, cookieData, flags, reserved)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"WinINet.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static int InternetSetCookieEx(
	String^ urlName, 
	String^ cookieName, 
	String^ cookieData, 
	int flags, 
	IntPtr reserved
)
```

**F#**<br />
``` F#
[<DllImportAttribute("WinINet.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member InternetSetCookieEx : 
        urlName : string * 
        cookieName : string * 
        cookieData : string * 
        flags : int * 
        reserved : IntPtr -> int 

```


#### Parameters
&nbsp;<dl><dt>urlName</dt><dd>Type: System.String<br />The URL for which the cookie should be set.</dd><dt>cookieName</dt><dd>Type: System.String<br />The name to be associated with the cookie data. If this parameter is a null reference (`Nothing` in Visual Basic), no name is associated with the cookie.</dd><dt>cookieData</dt><dd>Type: System.String<br />Actual data to be associated with the URL.</dd><dt>flags</dt><dd>Type: System.Int32<br />Flags that control how the function retrieves cookie data:.</dd><dt>reserved</dt><dd>Type: System.IntPtr<br />Zero, or contains a pointer to a Platform-for-Privacy-Protection (P3P) header to be associated with the cookie.</dd></dl>

#### Return Value
Type: Int32<br />Returns a member of the InternetCookieState enumeration if successful, or zero (0) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wininet/nf-wininet-internetsetcookiea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wininet/nf-wininet-internetsetcookiea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />