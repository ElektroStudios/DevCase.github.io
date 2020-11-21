# NativeMethods.SwitchDesktop Method 
 

Makes the specified desktop visible and activates it. This enables the desktop to receive input from the user. 

 The calling process must have DESKTOP_SWITCHDESKTOP access to the desktop for the SwitchDesktop(IntPtr) function to succeed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool SwitchDesktop(
	IntPtr hDesktop
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SwitchDesktop ( 
	hDesktop As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hDesktop As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.SwitchDesktop(hDesktop)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool SwitchDesktop(
	IntPtr hDesktop
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member SwitchDesktop : 
        hDesktop : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hDesktop</dt><dd>Type: System.IntPtr<br />A handle to the desktop. This handle is returned by the CreateDesktop and OpenDesktop functions.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-switchdesktop" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-switchdesktop</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />