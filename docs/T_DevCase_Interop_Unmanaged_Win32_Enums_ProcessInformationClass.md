# ProcessInformationClass Enumeration
 

Specifies the type of process information to be retrieved when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtQueryInformationProcess">NtQueryInformationProcess(IntPtr, ProcessInformationClass, ProcessBasicInformation, Int32, Int32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ProcessInformationClass
```

**VB**<br />
``` VB
Public Enumeration ProcessInformationClass
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessInformationClass
```

**C++**<br />
``` C++
public enum class ProcessInformationClass
```

**F#**<br />
``` F#
type ProcessInformationClass
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessInformationClass.ProcessBasicInformation">**ProcessBasicInformation**</td><td>0</td><td>Retrieves a pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessBasicInformation">ProcessBasicInformation</a> structure that can be used to determine whether the specified process is being debugged, and a unique value used by the system to identify the specified process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessInformationClass.ProcessDebugPort">**ProcessDebugPort**</td><td>7</td><td>Retrieves a IntPtr value that is the port number of the debugger for the process. 

 A nonzero value indicates that the process is being run under the control of a ring 3 debugger.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessInformationClass.ProcessWow64Information">**ProcessWow64Information**</td><td>26</td><td>Determines whether the process is running in the WOW64 environment (WOW64 is the x86 emulator that allows Win32-based applications to run on 64-bit Windows).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessInformationClass.ProcessImageFileName">**ProcessImageFileName**</td><td>27</td><td>Retrieves a UNICODE_STRING value containing the name of the image file for the process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessInformationClass.ProcessBreakOnTermination">**ProcessBreakOnTermination**</td><td>29</td><td>Retrieves a Int64 value indicating whether the process is considered critical. 

 Note: This value can be used starting in Windows XP with SP3. Starting in Windows 8.1, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_IsProcessCritical">IsProcessCritical(SafeProcessHandle, Boolean)</a> should be used instead.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessInformationClass.ProcessSubsystemInformation">**ProcessSubsystemInformation**</td><td>75</td><td>Retrieves a SUBSYSTEM_INFORMATION_TYPE value indicating the subsystem type of the process. 

 The buffer pointed to by the ProcessInformation parameter should be large enough to hold a single SUBSYSTEM_INFORMATION_TYPE enumeration.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winternl/nf-winternl-ntqueryinformationprocess" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winternl/nf-winternl-ntqueryinformationprocess</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />