# NativeMethods.SetDoubleClickTime Method 
 

Sets the double-click time for the mouse. 

 A double-click is a series of two clicks of the mouse button, the second occurring within a specified time after the first. 

 The double-click time is the maximum number of milliseconds that may occur between the first and second click of a double-click. 

 The maximum double-click time is `5000` milliseconds.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool SetDoubleClickTime(
	int interval
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function SetDoubleClickTime ( 
	interval As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim interval As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.SetDoubleClickTime(interval)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool SetDoubleClickTime(
	int interval
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member SetDoubleClickTime : 
        interval : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>interval</dt><dd>Type: System.Int32<br />The number of milliseconds that may occur between the first and second clicks of a double-click. 

 If this parameter is set to 0, the system uses the default double-click time of `500` milliseconds. 

 If this parameter value is greater than `5000` milliseconds, the system sets the value to `5000` milliseconds.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646263%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646263%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />