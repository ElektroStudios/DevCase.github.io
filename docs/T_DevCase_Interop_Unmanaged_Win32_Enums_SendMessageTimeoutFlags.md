# SendMessageTimeoutFlags Enumeration
 

Flags for `fuFlags` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendMessageTimeout">SendMessageTimeout(IntPtr, EditControlMessages, IntPtr, IntPtr, SendMessageTimeoutFlags, Int32, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SendMessageTimeoutFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SendMessageTimeoutFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As SendMessageTimeoutFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SendMessageTimeoutFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SendMessageTimeoutFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SendMessageTimeoutFlags.Normal">**Normal**</td><td>0</td><td>The calling thread is not prevented from processing other requests while waiting for the function to return.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SendMessageTimeoutFlags.Block">**Block**</td><td>1</td><td>Prevents the calling thread from processing any other requests until the function returns.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SendMessageTimeoutFlags.AbortIfHung">**AbortIfHung**</td><td>2</td><td>The function returns without waiting for the time-out period to elapse if the receiving thread appears to not respond or "hangs."</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SendMessageTimeoutFlags.NoTimeoutIfNotHung">**NoTimeoutIfNotHung**</td><td>8</td><td>The function does not enforce the time-out period as long as the receiving thread is processing messages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SendMessageTimeoutFlags.ErrorOnExit">**ErrorOnExit**</td><td>32</td><td>The function should return 0 if the receiving window is destroyed or its owning thread dies while the message is being processed.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms644952%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms644952%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />