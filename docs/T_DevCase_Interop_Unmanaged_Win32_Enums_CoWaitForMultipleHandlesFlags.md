# CoWaitForMultipleHandlesFlags Enumeration
 

Specifies the behavior of the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CoWaitForMultipleHandles">CoWaitForMultipleHandles(CoWaitForMultipleHandlesFlags, UInt32, UInt32, IntPtr[], UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum CoWaitForMultipleHandlesFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration CoWaitForMultipleHandlesFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As CoWaitForMultipleHandlesFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class CoWaitForMultipleHandlesFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type CoWaitForMultipleHandlesFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CoWaitForMultipleHandlesFlags.Default">**Default**</td><td>0</td><td>Dispatch calls needed for marshaling without dispatching arbitrary calls.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CoWaitForMultipleHandlesFlags.WaitAll">**WaitAll**</td><td>1</td><td>If set, the call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CoWaitForMultipleHandles">CoWaitForMultipleHandles(CoWaitForMultipleHandlesFlags, UInt32, UInt32, IntPtr[], UInt32)</a> will return <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> only when all handles associated with the synchronization object have been signaled and an input event has been received, all at the same time. 

 In this case, the behavior of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CoWaitForMultipleHandles">CoWaitForMultipleHandles(CoWaitForMultipleHandlesFlags, UInt32, UInt32, IntPtr[], UInt32)</a> corresponds to the behavior of the MsgWaitForMultipleObjectsEx function with the flags parameter set to MWMO_WAITALL. 

 If WaitAll is not set, the call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CoWaitForMultipleHandles">CoWaitForMultipleHandles(CoWaitForMultipleHandlesFlags, UInt32, UInt32, IntPtr[], UInt32)</a> will return <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> as soon as any handle associated with the synchronization object has been signaled, regardless of whether an input event is received.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CoWaitForMultipleHandlesFlags.Alertable">**Alertable**</td><td>2</td><td>If set, the call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CoWaitForMultipleHandles">CoWaitForMultipleHandles(CoWaitForMultipleHandlesFlags, UInt32, UInt32, IntPtr[], UInt32)</a> will return <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if an asynchronous procedure call (APC) has been queued to the calling thread with a call to the QueueUserAPC function, even if no handle has been signaled.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CoWaitForMultipleHandlesFlags.InputAvailable">**InputAvailable**</td><td>4</td><td>If set, the call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CoWaitForMultipleHandles">CoWaitForMultipleHandles(CoWaitForMultipleHandlesFlags, UInt32, UInt32, IntPtr[], UInt32)</a> will return <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if input exists for the queue, even if the input has been seen (but not removed) using a call to another function, such as PeekMessage.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CoWaitForMultipleHandlesFlags.DispatchCalls">**DispatchCalls**</td><td>8</td><td>Dispatch calls from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CoWaitForMultipleHandles">CoWaitForMultipleHandles(CoWaitForMultipleHandlesFlags, UInt32, UInt32, IntPtr[], UInt32)</a> in an ASTA. 

 Default is no call dispatch. 

 This value has no meaning in other apartment types and is ignored.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CoWaitForMultipleHandlesFlags.DispatchWindowMessages">**DispatchWindowMessages**</td><td>16</td><td>Enables dispatch of window messages from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CoWaitForMultipleHandles">CoWaitForMultipleHandles(CoWaitForMultipleHandlesFlags, UInt32, UInt32, IntPtr[], UInt32)</a> in an ASTA or STA. 

 Default in ASTA is no window messages dispatched, default in STA is only a small set of special-cased messages dispatched. 

 The value has no meaning in MTA and is ignored.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/ne-combaseapi-tagcowait_flags" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/ne-combaseapi-tagcowait_flags</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />