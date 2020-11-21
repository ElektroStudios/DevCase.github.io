# MonitorFromFlags Enumeration
 

Determines the function's return value when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MonitorFromWindow">MonitorFromWindow(IntPtr, MonitorFromFlags)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MonitorFromPoint">MonitorFromPoint(NativePoint, MonitorFromFlags)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MonitorFromRect">MonitorFromRect(NativeRectangle, MonitorFromFlags)</a> functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum MonitorFromFlags
```

**VB**<br />
``` VB
Public Enumeration MonitorFromFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As MonitorFromFlags
```

**C++**<br />
``` C++
public enum class MonitorFromFlags
```

**F#**<br />
``` F#
type MonitorFromFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MonitorFromFlags.DefaultToNull">**DefaultToNull**</td><td>0</td><td>Returns a null reference (`Nothing` in Visual Basic).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MonitorFromFlags.DefaultToPrimary">**DefaultToPrimary**</td><td>1</td><td>Returns a handle to the primary display monitor.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MonitorFromFlags.DefaultToNearest">**DefaultToNearest**</td><td>2</td><td>Returns a handle to the display monitor that is nearest to the window.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd145064%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd145064%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />