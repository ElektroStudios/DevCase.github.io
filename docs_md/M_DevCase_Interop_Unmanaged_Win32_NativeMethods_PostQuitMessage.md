# NativeMethods.PostQuitMessage Method 
 

Indicates to the system that a thread has made a request to terminate (quit). 

 It is typically used in response to a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Destroy</a> message.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static void PostQuitMessage(
	[OptionalAttribute] int exitCode
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Sub PostQuitMessage ( 
	<OptionalAttribute> exitCode As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim exitCode As Integer

NativeMethods.PostQuitMessage(exitCode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static void PostQuitMessage(
	[OptionalAttribute] int exitCode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member PostQuitMessage : 
        [<OptionalAttribute>] exitCode : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>exitCode (Optional)</dt><dd>Type: System.Int32<br />The application exit code. This value is used as the wParam parameter of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Quit</a> message.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-postquitmessage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-postquitmessage</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />