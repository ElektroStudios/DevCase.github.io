# PssProcessInformation Structure
 

Holds process information returned by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PssQuerySnapshot">PssQuerySnapshot(IntPtr, PssQueryInformationClass, IntPtr, UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct PssProcessInformation
```

**VB**<br />
``` VB
Public Structure PssProcessInformation
```

**VB Usage**<br />
``` VB Usage
Dim instance As PssProcessInformation
```

**C++**<br />
``` C++
public value class PssProcessInformation
```

**F#**<br />
``` F#
[<SealedAttribute>]
type PssProcessInformation =  struct end
```

The PssProcessInformation type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_AffinityMask">AffinityMask</a></td><td>
The affinity mask of the process.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_BasePriority">BasePriority</a></td><td>
The base priority level of the process.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_CreateTime">CreateTime</a></td><td>
The time the process was created.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_ExecuteFlags">ExecuteFlags</a></td><td>
Reserved for use by the operating system.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_ExitStatus">ExitStatus</a></td><td>
The exit code of the process. If the process has not exited, this is set to `STILL_ACTIVE` (259).</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_ExitTime">ExitTime</a></td><td>
If the process exited, the time of the exit.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_Flags">Flags</a></td><td>
Flags about the process.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_ImageFileName">ImageFileName</a></td><td>
The full path to the process executable. If the path exceeds the allocated buffer size, it is truncated.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_KernelTime">KernelTime</a></td><td>
The amount of time the process spent executing in kernel-mode.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_PageFaultCount">PageFaultCount</a></td><td>
A memory usage counter.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_PagefileUsage">PagefileUsage</a></td><td>
A memory usage counter.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_ParentProcessId">ParentProcessId</a></td><td>
The parent process ID.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_PeakPagefileUsage">PeakPagefileUsage</a></td><td>
A memory usage counter.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_PeakVirtualSize">PeakVirtualSize</a></td><td>
A memory usage counter.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_PeakWorkingSetSize">PeakWorkingSetSize</a></td><td>
A memory usage counter.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_PebBaseAddress">PebBaseAddress</a></td><td>
The address to the process environment block (PEB). Reserved for use by the operating system.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_PriorityClass">PriorityClass</a></td><td>
The priority class.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_PrivateUsage">PrivateUsage</a></td><td>
A memory usage counter.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_ProcessId">ProcessId</a></td><td>
The process ID.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_QuotaNonPagedPoolUsage">QuotaNonPagedPoolUsage</a></td><td>
A memory usage counter.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_QuotaPagedPoolUsage">QuotaPagedPoolUsage</a></td><td>
A memory usage counter.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_QuotaPeakNonPagedPoolUsage">QuotaPeakNonPagedPoolUsage</a></td><td>
A memory usage counter.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_QuotaPeakPagedPoolUsage">QuotaPeakPagedPoolUsage</a></td><td>
A memory usage counter.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_UserTime">UserTime</a></td><td>
The amount of time the process spent executing in user-mode.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_VirtualSize">VirtualSize</a></td><td>
A memory usage counter.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssProcessInformation_WorkingSetSize">WorkingSetSize</a></td><td>
A memory usage counter.</td></tr></table>&nbsp;
<a href="#pssprocessinformation-structure">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#pssprocessinformation-structure">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/desktop/api/processsnapshot/ns-processsnapshot-pss_process_information" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/desktop/api/processsnapshot/ns-processsnapshot-pss_process_information</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />