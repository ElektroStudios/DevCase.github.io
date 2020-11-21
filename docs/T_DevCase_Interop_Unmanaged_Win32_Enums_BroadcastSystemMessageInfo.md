# BroadcastSystemMessageInfo Enumeration
 

Specifies information about the recipients of a message when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BroadcastSystemMessage">BroadcastSystemMessage(BroadcastSystemMessageFlags, BroadcastSystemMessageInfo, WindowMessages, IntPtr, IntPtr)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BroadcastSystemMessageEx">BroadcastSystemMessageEx(BroadcastSystemMessageFlags, BroadcastSystemMessageInfo, WindowMessages, IntPtr, IntPtr, BroadcastSystemMessageExInfo)</a> functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum BroadcastSystemMessageInfo
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration BroadcastSystemMessageInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As BroadcastSystemMessageInfo
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class BroadcastSystemMessageInfo
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type BroadcastSystemMessageInfo
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageInfo.AllComponents">**AllComponents**</td><td>0</td><td>Broadcast to all system components.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageInfo.AllDesktops">**AllDesktops**</td><td>16</td><td>Broadcast to all desktops. Requires the SE_TCB_NAME privilege.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageInfo.Applications">**Applications**</td><td>8</td><td>Broadcast to applications.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageInfo.Vxds">**Vxds**</td><td>1</td><td>( Not documented. )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageInfo.NetDriver">**NetDriver**</td><td>2</td><td>( Not documented. )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BroadcastSystemMessageInfo.InstallableDrivers">**InstallableDrivers**</td><td>4</td><td>( Not documented. )</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-broadcastsystemmessage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-broadcastsystemmessage</a><a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-broadcastsystemmessageexa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-broadcastsystemmessageexa</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />