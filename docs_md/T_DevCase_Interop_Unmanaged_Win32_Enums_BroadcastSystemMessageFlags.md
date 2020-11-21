# BroadcastSystemMessageFlags Enumeration
 

Specifies the broadcast options when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BroadcastSystemMessage">BroadcastSystemMessage(BroadcastSystemMessageFlags, BroadcastSystemMessageInfo, WindowMessages, IntPtr, IntPtr)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BroadcastSystemMessageEx">BroadcastSystemMessageEx(BroadcastSystemMessageFlags, BroadcastSystemMessageInfo, WindowMessages, IntPtr, IntPtr, BroadcastSystemMessageExInfo)</a> functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum BroadcastSystemMessageFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration BroadcastSystemMessageFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As BroadcastSystemMessageFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class BroadcastSystemMessageFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type BroadcastSystemMessageFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageFlags.AllowSetForegroundWindow">**AllowSetForegroundWindow**</td><td>128</td><td>Enables the recipient to set the foreground window while processing the message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageFlags.FlushDisk">**FlushDisk**</td><td>4</td><td>Flushes the disk after each recipient processes the message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageFlags.ForceIfHung">**ForceIfHung**</td><td>32</td><td>Continues to broadcast the message, even if the time-out period elapses or one of the recipients is not responding.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageFlags.IgnoreCurrentTask">**IgnoreCurrentTask**</td><td>2</td><td>Does not send the message to windows that belong to the current task. 

 This prevents an application from receiving its own message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageFlags.NoHang">**NoHang**</td><td>8</td><td>Forces a non-responsive application to time out. 

 If one of the recipients times out, do not continue broadcasting the message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageFlags.NoTimeoutIfNotHung">**NoTimeoutIfNotHung**</td><td>64</td><td>Waits for a response to the message, as long as the recipient is not being unresponsive. 

 Does not time out.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageFlags.PostMessage">**PostMessage**</td><td>16</td><td>Posts the message. 

 Do not use in combination with Query.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageFlags.Query">**Query**</td><td>1</td><td>Sends the message to one recipient at a time, sending to a subsequent recipient only if the current recipient returns `true` (`True` in Visual Basic).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageFlags.SendNotifyMessage">**SendNotifyMessage**</td><td>256</td><td>Sends the message using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendNotifyMessage">SendNotifyMessage(IntPtr, WindowMessages, IntPtr, IntPtr)</a> function. 

 Do not use in combination with Query.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageFlags.ReturnHDesk">**ReturnHDesk**</td><td>512</td><td>( Not documented. )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageFlags.Luid">**Luid**</td><td>1024</td><td>( Not documented. )</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-broadcastsystemmessage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-broadcastsystemmessage</a><a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-broadcastsystemmessageexa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-broadcastsystemmessageexa</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />