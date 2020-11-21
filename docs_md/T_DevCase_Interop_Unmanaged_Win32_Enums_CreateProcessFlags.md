# CreateProcessFlags Enumeration
 

Specifies the changes to be applied for the active desktop. 

 These flags are used by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcess">CreateProcess(String, StringBuilder, SecurityAttributes, SecurityAttributes, Boolean, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcessAsUser">CreateProcessAsUser(IntPtr, String, StringBuilder, SecurityAttributes, SecurityAttributes, Boolean, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcessWithLogon">CreateProcessWithLogon(String, String, String, ProcessLogonFlags, String, StringBuilder, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a>, and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcessWithToken">CreateProcessWithToken(IntPtr, ProcessLogonFlags, String, StringBuilder, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a> functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum CreateProcessFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration CreateProcessFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As CreateProcessFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class CreateProcessFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type CreateProcessFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.DebugProcess">**DebugProcess**</td><td>1</td><td>The calling thread starts and debugs the new process and all child processes created by the new process. It can receive all related debug events using the WaitForDebugEvent function. 

 A process that uses DebugProcess becomes the root of a debugging chain. This continues until another process in the chain is created with DebugProcess. 

 If this flag Is combined With DebugOnlyThisProcess, the caller debugs only the New process, not any child processes.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.DebugOnlyThisProcess">**DebugOnlyThisProcess**</td><td>2</td><td>The calling thread starts and debugs the new process. It can receive all related debug events using the WaitForDebugEvent function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.CreateSuspended">**CreateSuspended**</td><td>4</td><td>The primary thread of the new process is created in a suspended state, and does not run until the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ResumeThread">ResumeThread(SafeAccessTokenHandle)</a> function is called.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.DetachedProcess">**DetachedProcess**</td><td>8</td><td>For console processes, the new process does not inherit its parent's console (the default). The new process can call the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_AllocConsole">AllocConsole()</a> function at a later time to create a console. 

 This value cannot be used with CreateNewConsole.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.CreateNewConsole">**CreateNewConsole**</td><td>16</td><td>The new process has a new console, instead of inheriting its parent's console (the default). 

 This flag cannot be used With DetachedProcess</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.PriorityClassNormal">**PriorityClassNormal**</td><td>32</td><td>Use normal priority class for the new process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.PriorityClassIdle">**PriorityClassIdle**</td><td>64</td><td>Use IDLE priority class for the new process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.PriorityClassHigh">**PriorityClassHigh**</td><td>128</td><td>Use high priority class for the new process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.PriorityClassRealTime">**PriorityClassRealTime**</td><td>256</td><td>Use real-time priority class for the new process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.CreateNewProcessGroup">**CreateNewProcessGroup**</td><td>512</td><td>The new process is the root process of a new process group. The process group includes all processes that are descendants of this root process. The process identifier of the new process group is the same as the process identifier, which is returned in the lpProcessInformation parameter. 

 Process groups are used by the GenerateConsoleCtrlEvent function to enable sending a CTRL+BREAK signal to a group of console processes. 

 If this flag is specified, CTRL+C signals will be disabled for all processes within the new process group. 

 This flag is ignored if specified with CreateNewConsole.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.CreateUnicodeEnvironment">**CreateUnicodeEnvironment**</td><td>1024</td><td>If this flag is set, the environment block pointed to by lpEnvironment parameter uses Unicode characters. Otherwise, the environment block uses ANSI characters.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.CreateSeparateWowVdm">**CreateSeparateWowVdm**</td><td>2048</td><td>This flag is valid only when starting a 16-bit Windows-based application. If set, the new process runs in a private Virtual DOS Machine (VDM). 

 By default, all 16-bit Windows-based applications run as threads in a single, shared VDM. The advantage of running separately is that a crash only terminates the single VDM; any other programs running in distinct VDMs continue to function normally. 

 Also, 16-bit Windows-based applications that are run in separate VDMs have separate input queues. That means that if one application stops responding momentarily, applications in separate VDMs continue to receive input. The disadvantage of running separately is that it takes significantly more memory to do so. 

 You should use this flag only if the user requests that 16-bit applications should run in their own VDM.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.CreateSharedWowVdm">**CreateSharedWowVdm**</td><td>4096</td><td>The flag is valid only when starting a 16-bit Windows-based application. If the DefaultSeparateVDM switch in the Windows section of WIN.INI is TRUE, this flag overrides the switch. The new process is run in the shared Virtual DOS Machine.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.CreateForceDos">**CreateForceDos**</td><td>8192</td><td>**UNDOCUMENTED**.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.PriorityClassBelowNormal">**PriorityClassBelowNormal**</td><td>16384</td><td>Use below normal priority class for the new process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.PriorityClassAboveNormal">**PriorityClassAboveNormal**</td><td>32768</td><td>Use above normal priority class for the new process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.InheritParentAffinity">**InheritParentAffinity**</td><td>65536</td><td>The process inherits its parent's affinity. If the parent process has threads in more than one processor group, the new process inherits the group-relative affinity of an arbitrary group in use by the parent.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.InheritCallerAffinity">**InheritCallerAffinity**</td><td>131072</td><td>**UNDOCUMENTED**.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.CreateProtectedProcess">**CreateProtectedProcess**</td><td>262144</td><td>The process is to be run as a protected process. The system restricts access to protected processes and the threads of protected processes. 

 To activate a protected process, the binary must have a special signature. This signature is provided by Microsoft but not currently available for non-Microsoft binaries. There are currently four protected processes: media foundation, audio engine, Windows error reporting, and system. Components that load into these binaries must also be signed. Multimedia companies can leverage the first two protected processes.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.CreateSecureProcess">**CreateSecureProcess**</td><td>4194304</td><td>This flag allows secure processes, that run in the Virtualization-Based Security environment, to launch.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.ExtendedStartupInfoPresent">**ExtendedStartupInfoPresent**</td><td>524288</td><td>The process is created with extended startup information; the lpStartupInfo parameter specifies a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfoEx">ProcessStartupInfoEx</a> structure.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.ProcessModeBackgroundBegin">**ProcessModeBackgroundBegin**</td><td>1048576</td><td>**UNDOCUMENTED**.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.ProcessModeBackgroundEnd">**ProcessModeBackgroundEnd**</td><td>2097152</td><td>**UNDOCUMENTED**.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.CreateBreakawayFromJob">**CreateBreakawayFromJob**</td><td>16777216</td><td>The child processes of a process associated with a job are not associated with the job. 

 If the calling process Is Not associated With a job, this constant has no effect. If the calling process Is associated With a job, the job must set the JOB_OBJECT_LIMIT_BREAKAWAY_OK limit.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.CreatePreserveCodeAuthzLevel">**CreatePreserveCodeAuthzLevel**</td><td>33554432</td><td>Allows the caller to execute a child process that bypasses the process restrictions that would normally be applied automatically to the process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.CreateDefaultErrorMode">**CreateDefaultErrorMode**</td><td>67108864</td><td>The new process does not inherit the error mode of the calling process. Instead, the new process gets the default error mode. 

 This feature is particularly useful for multithreaded shell applications that run with hard errors disabled. 

 The default behavior is for the new process to inherit the error mode of the caller. Setting this flag changes that default behavior.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.CreateNoWindow">**CreateNoWindow**</td><td>134217728</td><td>The process is a console application that is being run without a console window. Therefore, the console handle for the application is not set. 

 This flag is ignored if the application is not a console application, or if it is used with either CreateNewConsole or DetachedProcess.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.ProfileUser">**ProfileUser**</td><td>268435456</td><td>**UNDOCUMENTED**.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.ProfileKernel">**ProfileKernel**</td><td>536870912</td><td>**UNDOCUMENTED**.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.ProfileServer">**ProfileServer**</td><td>1073741824</td><td>**UNDOCUMENTED**.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateProcessFlags.CreateIgnoreSystemDefault">**CreateIgnoreSystemDefault**</td><td>2147483648</td><td>**UNDOCUMENTED**.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/ProcThread/process-creation-flags" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/ProcThread/process-creation-flags</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />