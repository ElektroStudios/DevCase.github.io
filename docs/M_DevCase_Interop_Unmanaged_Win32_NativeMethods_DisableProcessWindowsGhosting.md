# NativeMethods.DisableProcessWindowsGhosting Method 
 

Disables the window ghosting feature for the calling GUI process. 

 Window ghosting is a Windows Manager feature that lets the user minimize, move, or close the main window of an application that is not responding.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static void DisableProcessWindowsGhosting()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Sub DisableProcessWindowsGhosting
```

**VB Usage**<br />
``` VB Usage

NativeMethods.DisableProcessWindowsGhosting()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static void DisableProcessWindowsGhosting()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member DisableProcessWindowsGhosting : unit -> unit 

```


## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-disableprocesswindowsghosting" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-disableprocesswindowsghosting</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />