# NativeMethods.GetProcessWindowStation Method 
 

Retrieves a handle to the current window station for the calling process..

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr GetProcessWindowStation()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetProcessWindowStation As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IntPtr

returnValue = NativeMethods.GetProcessWindowStation()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr GetProcessWindowStation()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetProcessWindowStation : unit -> IntPtr 

```


#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the window station. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getprocesswindowstation" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getprocesswindowstation</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />