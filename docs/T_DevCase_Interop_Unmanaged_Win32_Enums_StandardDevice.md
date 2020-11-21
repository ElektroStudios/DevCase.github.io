# StandardDevice Enumeration
 

Specifies a standard device (standard input, standard output, or standard error). 

 For <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetStdHandle">GetStdHandle(StandardDevice)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetStdHandle">SetStdHandle(StandardDevice, IntPtr)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetStdHandleEx">SetStdHandleEx(StandardDevice, IntPtr, IntPtr)</a> functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum StandardDevice
```

**VB**<br />
``` VB
Public Enumeration StandardDevice
```

**VB Usage**<br />
``` VB Usage
Dim instance As StandardDevice
```

**C++**<br />
``` C++
public enum class StandardDevice
```

**F#**<br />
``` F#
type StandardDevice
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.StandardDevice.StandardInput">**StandardInput**</td><td>-10</td><td>The standard input device. 

 Initially, this is the console input buffer, CONIN$.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.StandardDevice.StandardOutput">**StandardOutput**</td><td>-11</td><td>The standard output device. 

 Initially, this is the active console screen buffer, CONOUT$.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.StandardDevice.StandardError">**StandardError**</td><td>-12</td><td>The standard error device. 

 Initially, this is the active console screen buffer, CONOUT$.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/getstdhandle" target="_blank">https://docs.microsoft.com/en-us/windows/console/getstdhandle</a><a href="https://docs.microsoft.com/en-us/windows/console/setstdhandle" target="_blank">https://docs.microsoft.com/en-us/windows/console/setstdhandle</a><a href="http://undoc.airesoft.co.uk/kernel32.dll/SetStdHandleEx.php" target="_blank">http://undoc.airesoft.co.uk/kernel32.dll/SetStdHandleEx.php</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />