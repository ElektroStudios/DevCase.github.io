# QueueStatusFlags Enumeration
 

Specifies the types of messages for which to check when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetQueueStatus">GetQueueStatus(QueueStatusFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum QueueStatusFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration QueueStatusFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As QueueStatusFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class QueueStatusFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type QueueStatusFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.AllEvents">**AllEvents**</td><td>7359</td><td>An input, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Timer</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Hotkey</a>, or posted message is in the queue.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.AllInput">**AllInput**</td><td>7423</td><td>Any message is in the queue.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.AllPostMessage">**AllPostMessage**</td><td>256</td><td>A posted message (other than those listed here) is in the queue.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.Hotkey">**Hotkey**</td><td>128</td><td>A WM_HOTKEY message is in the queue.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.Input">**Input**</td><td>7175</td><td>An input message is in the queue.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.Key">**Key**</td><td>1</td><td>A <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_KeyUp</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_KeyDown</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SysKeyUp</a>, or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SysKeyDown</a> message is in the queue.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.Mouse">**Mouse**</td><td>6</td><td>A <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_MouseMove</a> message or mouse-button message (<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_LButtonDown</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_RButtonDown</a>, and so on).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.MouseButton">**MouseButton**</td><td>4</td><td>A mouse-button message (<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_LButtonDown</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_RButtonDown</a>, and so on).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.MouseMove">**MouseMove**</td><td>2</td><td>A <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_MouseMove</a> message is in the queue.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.Paint">**Paint**</td><td>32</td><td>A <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a> message is in the queue.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.PostMessage">**PostMessage**</td><td>8</td><td>A posted message (other than those listed here) is in the queue.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.RawInput">**RawInput**</td><td>1024</td><td>A raw input message is in the queue. See <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInput">RawInput</a>.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.SendMessage">**SendMessage**</td><td>64</td><td>A message sent by another thread or application is in the queue.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.Timer">**Timer**</td><td>16</td><td>A <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Timer</a> message is in the queue.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.Touch">**Touch**</td><td>2048</td><td>( Not documented. )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueueStatusFlags.Pointer">**Pointer**</td><td>4096</td><td>( Not documented. )</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getqueuestatus" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getqueuestatus</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />