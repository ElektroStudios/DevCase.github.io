# NativeMethods.GetDoubleClickTime Method 
 

Retrieves the current double-click time for the mouse. 

 A double-click is a series of two clicks of the mouse button, the second occurring within a specified time after the first. 

 The double-click time is the maximum number of milliseconds that may occur between the first and second click of a double-click. 

 The maximum double-click time is `5000` milliseconds.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static int GetDoubleClickTime()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function GetDoubleClickTime As Integer
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Integer

returnValue = NativeMethods.GetDoubleClickTime()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static int GetDoubleClickTime()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member GetDoubleClickTime : unit -> int 

```


#### Return Value
Type: Int32<br />The return value specifies the current double-click time, in milliseconds. 

 The maximum return value is `5000` milliseconds.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646258%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646258%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />