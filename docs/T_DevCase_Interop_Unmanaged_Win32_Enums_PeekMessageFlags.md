# PeekMessageFlags Enumeration
 

Specifies how messages are to be handled when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PeekMessage">PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum PeekMessageFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration PeekMessageFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As PeekMessageFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class PeekMessageFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type PeekMessageFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PeekMessageFlags.NoRemove">**NoRemove**</td><td>0</td><td>Messages are not removed from the queue after processing by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PeekMessage">PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags)</a>.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PeekMessageFlags.Remove">**Remove**</td><td>1</td><td>Messages are removed from the queue after processing by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PeekMessage">PeekMessage(NativeMessage, IntPtr, UInt32, UInt32, PeekMessageFlags)</a>.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PeekMessageFlags.NoYield">**NoYield**</td><td>2</td><td>Prevents the system from releasing any thread that is waiting for the caller to go idle (see WaitForInputIdle). 

 Combine this value with either NoRemove or Remove.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PeekMessageFlags.QueueStatusInput">**QueueStatusInput**</td><td>470220800</td><td>Process mouse and keyboard messages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PeekMessageFlags.QueueStatusPostMessage">**QueueStatusPostMessage**</td><td>9961472</td><td>Process all posted messages, including timers and hotkeys.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PeekMessageFlags.QueueStatusPaint">**QueueStatusPaint**</td><td>2097152</td><td>Process paint messages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PeekMessageFlags.QueueStatusSendMessage">**QueueStatusSendMessage**</td><td>4194304</td><td>Process all sent messages.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-peekmessagea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-peekmessagea</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />