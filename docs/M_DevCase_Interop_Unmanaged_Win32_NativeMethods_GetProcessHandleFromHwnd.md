# NativeMethods.GetProcessHandleFromHwnd Method 
 

Retrieves a process handle from a window handle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("OleAcc.dll", ExactSpelling = true)]
public static IntPtr GetProcessHandleFromHwnd(
	IntPtr hwnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("OleAcc.dll", ExactSpelling := true>]
Public Shared Function GetProcessHandleFromHwnd ( 
	hwnd As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hwnd As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.GetProcessHandleFromHwnd(hwnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"OleAcc.dll", ExactSpelling = true)]
static IntPtr GetProcessHandleFromHwnd(
	IntPtr hwnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("OleAcc.dll", ExactSpelling = true)>]
static member GetProcessHandleFromHwnd : 
        hwnd : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hwnd</dt><dd>Type: System.IntPtr<br />\[Missing <param name="hwnd"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.GetProcessHandleFromHwnd(System.IntPtr)"\]</dd></dl>

#### Return Value
Type: IntPtr<br />If successful, returns the handle of the process that owns the window. 

 If not successful, returns Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/winauto/getprocesshandlefromhwnd" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/winauto/getprocesshandlefromhwnd</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />