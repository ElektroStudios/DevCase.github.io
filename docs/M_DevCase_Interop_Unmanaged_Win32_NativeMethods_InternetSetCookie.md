# NativeMethods.InternetSetCookie Method 
 

Creates a cookie associated with the specified URL.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("WinINet.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool InternetSetCookie(
	string urlName,
	string cookieName,
	string cookieData
)
```

**VB**<br />
``` VB
<DllImportAttribute("WinINet.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function InternetSetCookie ( 
	urlName As String,
	cookieName As String,
	cookieData As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim urlName As String
Dim cookieName As String
Dim cookieData As String
Dim returnValue As Boolean

returnValue = NativeMethods.InternetSetCookie(urlName, 
	cookieName, cookieData)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"WinINet.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool InternetSetCookie(
	String^ urlName, 
	String^ cookieName, 
	String^ cookieData
)
```

**F#**<br />
``` F#
[<DllImportAttribute("WinINet.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member InternetSetCookie : 
        urlName : string * 
        cookieName : string * 
        cookieData : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>urlName</dt><dd>Type: System.String<br />The URL for which the cookie should be set.</dd><dt>cookieName</dt><dd>Type: System.String<br />The name to be associated with the cookie data. If this parameter is a null reference (`Nothing` in Visual Basic), no name is associated with the cookie.</dd><dt>cookieData</dt><dd>Type: System.String<br />Actual data to be associated with the URL.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wininet/nf-wininet-internetsetcookiea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wininet/nf-wininet-internetsetcookiea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />