# NativeMethods.InternetClearAllPerSiteCookieDecisions Method 
 

Clears all decisions that were made about cookies on a site by site basis.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("WinINet.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static bool InternetClearAllPerSiteCookieDecisions()
```

**VB**<br />
``` VB
<DllImportAttribute("WinINet.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function InternetClearAllPerSiteCookieDecisions As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = NativeMethods.InternetClearAllPerSiteCookieDecisions()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"WinINet.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static bool InternetClearAllPerSiteCookieDecisions()
```

**F#**<br />
``` F#
[<DllImportAttribute("WinINet.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member InternetClearAllPerSiteCookieDecisions : unit -> bool 

```


#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if all decisions were cleared, or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wininet/nf-wininet-internetclearallpersitecookiedecisions" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wininet/nf-wininet-internetclearallpersitecookiedecisions</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />