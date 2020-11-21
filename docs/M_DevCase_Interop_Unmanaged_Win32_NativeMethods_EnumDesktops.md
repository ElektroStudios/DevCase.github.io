# NativeMethods.EnumDesktops Method 
 

Enumerates all desktops associated with the specified window station of the calling process. 

 The function passes the name of each desktop, in turn, to an application-defined callback function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool EnumDesktops(
	IntPtr hWinsta,
	Delegates.EnumDesktopProc enumFunc,
	IntPtr lParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function EnumDesktops ( 
	hWinsta As IntPtr,
	enumFunc As Delegates.EnumDesktopProc,
	lParam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWinsta As IntPtr
Dim enumFunc As Delegates.EnumDesktopProc
Dim lParam As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.EnumDesktops(hWinsta, 
	enumFunc, lParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool EnumDesktops(
	IntPtr hWinsta, 
	Delegates.EnumDesktopProc^ enumFunc, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member EnumDesktops : 
        hWinsta : IntPtr * 
        enumFunc : Delegates.EnumDesktopProc * 
        lParam : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWinsta</dt><dd>Type: System.IntPtr<br />A handle to the window station whose desktops are to be enumerated. 

 This handle is returned by the CreateWindowStation, GetProcessWindowStation, or OpenWindowStation function, and must have the WINSTA_ENUMDESKTOPS access right. 

 If this parameter is Zero, the current window station is used.</dd><dt>enumFunc</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumDesktopProc">DevCase.Interop.Unmanaged.Win32.Delegates.EnumDesktopProc</a><br />A pointer to an application-defined <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumDesktopProc">Delegates.EnumDesktopProc</a> callback function.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />An application-defined value to be passed to the callback function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, it returns the nonzero value returned by the callback function that was pointed to by lpEnumFunc. 

 If the function is unable to perform the enumeration, the return value is zero. 

 If the callback function fails, the return value is zero. 

 The callback function can call SetLastError to set an error code for the caller to retrieve by calling GetLastError.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-enumdesktopsa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-enumdesktopsa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />