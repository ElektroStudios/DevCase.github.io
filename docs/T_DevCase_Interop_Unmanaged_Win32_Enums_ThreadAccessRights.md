# ThreadAccessRights Enumeration
 

Specifies thread-specific access rights.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ThreadAccessRights
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ThreadAccessRights
```

**VB Usage**<br />
``` VB Usage
Dim instance As ThreadAccessRights
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ThreadAccessRights
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ThreadAccessRights
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.Delete">**Delete**</td><td>65536</td><td>Required to delete the object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.ReadControl">**ReadControl**</td><td>131072</td><td>Required to read information in the security descriptor for the object, not including the information in the `SACL`. 

 To read or write the `SACL`, you must request the `ACCESS_SYSTEM_SECURITY` access right.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.WriteDac">**WriteDac**</td><td>262144</td><td>Required to modify the `DACL` in the security descriptor for the object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.WriteOwner">**WriteOwner**</td><td>524288</td><td>Required to change the owner in the security descriptor for the object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.Synchronize">**Synchronize**</td><td>1048576</td><td>The right to use the object for synchronization. 

 This enables a thread to wait until the object is in the signaled state.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.Terminate">**Terminate**</td><td>1</td><td>Required to terminate a thread using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_TerminateThread">TerminateThread(SafeAccessTokenHandle, UInt32)</a> function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.SuspendResume">**SuspendResume**</td><td>2</td><td>Required to suspend or resume a thread using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SuspendThread32">SuspendThread32(SafeAccessTokenHandle)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SuspendThread64">SuspendThread64(SafeAccessTokenHandle)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ResumeThread">ResumeThread(SafeAccessTokenHandle)</a> functions.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.GetContext">**GetContext**</td><td>8</td><td>Required to read the context of a thread using `GetThreadContext` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.SetContext">**SetContext**</td><td>16</td><td>Required to write the context of a thread using `SetThreadContext` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.SetInformation">**SetInformation**</td><td>32</td><td>Required to set certain information in the thread object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.QueryInformation">**QueryInformation**</td><td>64</td><td>Required to read certain information from the thread object, such as the exit code using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetExitCodeThread">GetExitCodeThread(IntPtr, UInt32)</a> function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.SetThreadToken">**SetThreadToken**</td><td>128</td><td>Required to set the impersonation token for a thread using `SetThreadToken` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.Impersonate">**Impersonate**</td><td>256</td><td>Required to use a thread's security information directly without calling it by using a communication mechanism that provides impersonation services.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.DirectImpersonation">**DirectImpersonation**</td><td>512</td><td>Required for a server thread that impersonates a client.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.SetLimitedInformation">**SetLimitedInformation**</td><td>1024</td><td>Required to set certain information in the thread object. 

 A handle that has the SetInformation access right is automatically granted SetLimitedInformation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights.QueryLimitedInformation">**QueryLimitedInformation**</td><td>2048</td><td>Required to read certain information from the thread objects. 

 A handle that has the QueryInformation access right is automatically granted QueryLimitedInformation.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms686769%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms686769%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />