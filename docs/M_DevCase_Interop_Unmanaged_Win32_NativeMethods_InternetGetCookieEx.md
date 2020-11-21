# NativeMethods.InternetGetCookieEx Method 
 

Retrieves data stored in cookies associated with a specified URL. 

 Unlike <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_InternetGetCookie">InternetGetCookie(String, String, StringBuilder, UInt32)</a> function, InternetGetCookieEx(String, String, StringBuilder, UInt32, Int32, IntPtr) can be used to restrict data retrieved to a single cookie name or, by policy, associated with untrusted sites or third-party cookies.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("WinINet.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool InternetGetCookieEx(
	string urlName,
	string cookieName,
	StringBuilder cookieData,
	ref uint refCookieSize,
	int flags,
	IntPtr reserved
)
```

**VB**<br />
``` VB
<DllImportAttribute("WinINet.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function InternetGetCookieEx ( 
	urlName As String,
	cookieName As String,
	cookieData As StringBuilder,
	ByRef refCookieSize As UInteger,
	flags As Integer,
	reserved As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim urlName As String
Dim cookieName As String
Dim cookieData As StringBuilder
Dim refCookieSize As UInteger
Dim flags As Integer
Dim reserved As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.InternetGetCookieEx(urlName, 
	cookieName, cookieData, refCookieSize, 
	flags, reserved)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"WinINet.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool InternetGetCookieEx(
	[InAttribute] String^ urlName, 
	[InAttribute] String^ cookieName, 
	StringBuilder^ cookieData, 
	unsigned int% refCookieSize, 
	int flags, 
	IntPtr reserved
)
```

**F#**<br />
``` F#
[<DllImportAttribute("WinINet.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member InternetGetCookieEx : 
        urlName : string * 
        cookieName : string * 
        cookieData : StringBuilder * 
        refCookieSize : uint32 byref * 
        flags : int * 
        reserved : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>urlName</dt><dd>Type: System.String<br />The URL for which cookies are to be retrieved.</dd><dt>cookieName</dt><dd>Type: System.String<br />Not implemented.</dd><dt>cookieData</dt><dd>Type: System.Text.StringBuilder<br />A buffer that receives the cookie data. This parameter can be NULL.</dd><dt>refCookieSize</dt><dd>Type: System.UInt32<br />A variable that specifies the size of the *cookieData* parameter buffer, in characters. 

 If the function succeeds, the buffer receives the amount of data copied to the *cookieData* buffer. 

 If *cookieData* is a null reference (`Nothing` in Visual Basic), this parameter receives a value that specifies the size of the buffer necessary to copy all the cookie data, expressed as a byte count.</dd><dt>flags</dt><dd>Type: System.Int32<br />A flag that controls how the function retrieves cookie data.</dd><dt>reserved</dt><dd>Type: System.IntPtr<br />Reserved for future use. Set to Zero.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wininet/nf-wininet-internetgetcookieexa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wininet/nf-wininet-internetgetcookieexa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />