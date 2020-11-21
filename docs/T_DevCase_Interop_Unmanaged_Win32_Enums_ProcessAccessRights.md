# ProcessAccessRights Enumeration
 

Specifies process-specific access rights.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ProcessAccessRights
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ProcessAccessRights
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessAccessRights
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ProcessAccessRights
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ProcessAccessRights
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.AllAccess">**AllAccess**</td><td>2097151</td><td>Combines all possible access rights for a process object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.Terminate">**Terminate**</td><td>1</td><td>Required to terminate a process using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_TerminateProcess">TerminateProcess(IntPtr, UInt32)</a>.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.CreateThread">**CreateThread**</td><td>2</td><td>Required to create a thread.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.SetSessionId">**SetSessionId**</td><td>4</td><td /></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.VirtualMemoryOperation">**VirtualMemoryOperation**</td><td>8</td><td>Required to perform an operation on the address space of a process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.VirtualMemoryRead">**VirtualMemoryRead**</td><td>16</td><td>Required to read memory in a process using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ReadProcessMemory">ReadProcessMemory(SafeProcessHandle, IntPtr, Byte[], IntPtr, IntPtr)</a> function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.VirtualMemoryWrite">**VirtualMemoryWrite**</td><td>32</td><td>Required to write to memory in a process using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WriteProcessMemory">WriteProcessMemory(IntPtr, IntPtr, Byte[], IntPtr, IntPtr)</a> function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.DuplicateHandle">**DuplicateHandle**</td><td>64</td><td>Required to duplicate a handle using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DuplicateHandle">DuplicateHandle(IntPtr, IntPtr, IntPtr, IntPtr, GenericAccessRights, Boolean, DuplicateHandleOptions)</a> function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.CreateProcess">**CreateProcess**</td><td>128</td><td>Required to create a process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.SetQuota">**SetQuota**</td><td>256</td><td>Required to set memory limits using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetProcessWorkingSetSize">SetProcessWorkingSetSize(IntPtr, IntPtr, IntPtr)</a> function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.SetInformation">**SetInformation**</td><td>512</td><td>Required to set certain information about a process, such as its priority class.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.QueryInformation">**QueryInformation**</td><td>1024</td><td>Required to retrieve certain information about a process, such as its token, exit code, and priority class.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.SuspendResume">**SuspendResume**</td><td>2048</td><td>Required to suspend or resume a process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.QueryLimitedInformation">**QueryLimitedInformation**</td><td>4096</td><td>Required to retrieve certain information about a process. 

 Note that a handle that has the QueryInformation access right is automatically granted QueryLimitedInformation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.Synchronize">**Synchronize**</td><td>1048576</td><td>Required to wait for the process to terminate using the wait functions.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.Delete">**Delete**</td><td>65536</td><td>Required to delete the object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.ReadControl">**ReadControl**</td><td>131072</td><td>Required to read information in the security descriptor for the object, not including the information in the `SACL`. 

 To read or write the `SACL`, you must request the `ACCESS_SYSTEM_SECURITY` access right.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.WriteDac">**WriteDac**</td><td>262144</td><td>Required to modify the `DACL` in the security descriptor for the object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.WriteOwner">**WriteOwner**</td><td>524288</td><td>Required to change the owner in the security descriptor for the object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights.StandardRightsRequired">**StandardRightsRequired**</td><td>983040</td><td>Combines <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">Delete</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">ReadControl</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">WriteDac</a>, and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">WriteOwner</a> access.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms684880%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms684880%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />