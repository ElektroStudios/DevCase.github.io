# ProcessPrivileges Enumeration
 

Specifies a process privilege.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ProcessPrivileges
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ProcessPrivileges
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessPrivileges
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ProcessPrivileges
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ProcessPrivileges
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.None">**None**</td><td>0</td><td>Any process privilege.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.AssignPrimaryTokenPrivilege">**AssignPrimaryTokenPrivilege**</td><td>1</td><td>Required to assign the primary token of a process. 

 User Right: Replace a process-level token.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.AuditPrivilege">**AuditPrivilege**</td><td>2</td><td>Required to generate audit-log entries. Give this privilege to secure servers, 

 User Right: Generate security audits.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.BackupPrivilege">**BackupPrivilege**</td><td>4</td><td>Required to perform backup operations. 

 This privilege causes the system to grant all read access control to any file, regardless of the access control list (ACL) specified for the file. 

 Any access request other than read is still evaluated with the ACL. 

 This privilege is required by the `RegSaveKey` and `RegSaveKeyExfunctions`. 

 User Right: Back up files and directories.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.ChangeNotifyPrivilege">**ChangeNotifyPrivilege**</td><td>8</td><td>Required to receive notifications of changes to files or directories. 

 This privilege also causes the system to skip all traversal access checks. 

 It is enabled by default for all users. 

 User Right: Bypass traverse checking.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.CreateGlobalPrivilege">**CreateGlobalPrivilege**</td><td>16</td><td>Required to create named file mapping objects in the global Namespace DevCase.Interop.during Terminal Services sessions. 

 This privilege is enabled by default for administrators, services, and the local system account 

 User Right: Create global objects.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.CreatePagefilePrivilege">**CreatePagefilePrivilege**</td><td>32</td><td>Required to create a paging file. 

 User Right: Create a pagefile.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.CreatePermanentPrivilege">**CreatePermanentPrivilege**</td><td>64</td><td>Required to create a permanent object. 

 User Right: Create permanent shared objects.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.CreateSymbolicLinkPrivilege">**CreateSymbolicLinkPrivilege**</td><td>128</td><td>Required to create a symbolic link. 

 User Right: Create symbolic links.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.CreateTokenPrivilege">**CreateTokenPrivilege**</td><td>256</td><td>Required to create a primary token. 

 User Right: Create a token object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.DebugPrivilege">**DebugPrivilege**</td><td>512</td><td>Required to debug and adjust the memory of a process owned by another account. 

 User Right: Debug programs.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.EnableDelegationPrivilege">**EnableDelegationPrivilege**</td><td>1024</td><td>Required to mark user and computer accounts as trusted for delegation. 

 User Right: Enable computer and user accounts to be trusted for delegation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.ImpersonatePrivilege">**ImpersonatePrivilege**</td><td>2048</td><td>Required to impersonate. 

 User Right: Impersonate a client after authentication.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.IncreaseBasePriorityPrivilege">**IncreaseBasePriorityPrivilege**</td><td>4096</td><td>Required to increase the base priority of a process. 

 User Right: Increase scheduling priority.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.IncreaseQuotaPrivilege">**IncreaseQuotaPrivilege**</td><td>8192</td><td>Required to increase the quota assigned to a process. 

 User Right: Adjust memory quotas for a process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.IncreaseWorkingSetPrivilege">**IncreaseWorkingSetPrivilege**</td><td>16384</td><td>Required to allocate more memory for applications that run in the context of users. 

 User Right: Increase a process working set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.LoadDriverPrivilege">**LoadDriverPrivilege**</td><td>32768</td><td>Required to load or unload a device driver. 

 User Right: Load and unload device drivers.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.LockMemoryPrivilege">**LockMemoryPrivilege**</td><td>65536</td><td>Required to lock physical pages in memory. 

 User Right: Lock pages in memory.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.MachineAccountPrivilege">**MachineAccountPrivilege**</td><td>131072</td><td>Required to create a computer account. 

 User Right: Add workstations to domain.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.ManageVolumePrivilege">**ManageVolumePrivilege**</td><td>262144</td><td>Required to enable volume management privileges. 

 User Right: Manage the files on a volume.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.ProfileSingleProcessPrivilege">**ProfileSingleProcessPrivilege**</td><td>524288</td><td>Required to gather profiling information for a single process. 

 User Right: Profile single process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.RelabelPrivilege">**RelabelPrivilege**</td><td>1048576</td><td>Required to modify the mandatory integrity level of an object. 

 User Right: Modify an object label.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.RemoteShutdownPrivilege">**RemoteShutdownPrivilege**</td><td>2097152</td><td>Required to shut down a system using a network request. 

 User Right: Force shutdown from a remote system.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.RestorePrivilege">**RestorePrivilege**</td><td>4194304</td><td>Required to perform restore operations. 

 This privilege causes the system to grant all write access control to any file, regardless of the ACL specified for the file. 

 Any access request other than write is still evaluated with the ACL. 

 Additionally, this privilege enables you to set any valid user or group SID as the owner of a file. 

 This privilege is required by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegLoadKey">RegLoadKey(RegistryHive, String, String)</a> function. 

 User Right: Restore files and directories.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.SecurityPrivilege">**SecurityPrivilege**</td><td>8388608</td><td>Required to perform a number of security-related functions, such as controlling and viewing audit messages. 

 This privilege identifies its holder as a security operator 

 User Right: Manage auditing and security log.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.ShutdownPrivilege">**ShutdownPrivilege**</td><td>16777216</td><td>Required to shut down a local system. 

 User Right: Shut down the system.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.SyncAgentPrivilege">**SyncAgentPrivilege**</td><td>33554432</td><td>Required for a domain controller to use the Lightweight Directory Access Protocol directory synchronization services. 

 This privilege enables the holder to read all objects and properties in the directory, regardless of the protection on the objects and properties. 

 By default, it is assigned to the Administrator and LocalSystem accounts on domain controllers. 

 User Right: Synchronize directory service data.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.SystemEnvironmentPrivilege">**SystemEnvironmentPrivilege**</td><td>67108864</td><td>Required to modify the nonvolatile `RAM` memory of systems that use this type of memory to store configuration information. 

 User Right: Modify firmware environment values.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.SystemProfilePrivilege">**SystemProfilePrivilege**</td><td>134217728</td><td>Required to gather profiling information for the entire system. 

 User Right: Profile system performance.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.SystemtimePrivilege">**SystemtimePrivilege**</td><td>268435456</td><td>Required to modify the system time. 

 User Right: Change the system time.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.TakeOwnershipPrivilege">**TakeOwnershipPrivilege**</td><td>536870912</td><td>Required to take ownership of an object without being granted discretionary access. 

 This privilege allows the owner value to be set only to those values that the holder may legitimately assign as the owner of an object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.TcbPrivilege">**TcbPrivilege**</td><td>1073741824</td><td>This privilege identifies its holder as part of the trusted computer base. 

 Some trusted protected subsystems are granted this privilege. 

 User Right: Act as part of the operating system.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.TimeZonePrivilege">**TimeZonePrivilege**</td><td>2147483648</td><td>Required to adjust the time zone associated with the computer's internal clock. 

 User Right: Change the time zone.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.TrustedCredManAccessPrivilege">**TrustedCredManAccessPrivilege**</td><td>4294967296</td><td>Required to access Credential Manager as a trusted caller. 

 User Right: Access Credential Manager as a trusted caller.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.UndockPrivilege">**UndockPrivilege**</td><td>8589934592</td><td>Required to undock a laptop. 

 User Right: Remove computer from docking station.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges.UnsolicitedInputPrivilege">**UnsolicitedInputPrivilege**</td><td>17179869184</td><td>Required to read unsolicited input from a terminal device. 

 User Right: Not applicable.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb530716%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb530716%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />