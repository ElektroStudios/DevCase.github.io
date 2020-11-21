# PssPerformanceCounters Structure
 

Holds performance counters information returned by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PssQuerySnapshot">PssQuerySnapshot(IntPtr, PssQueryInformationClass, IntPtr, UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct PssPerformanceCounters
```

**VB**<br />
``` VB
Public Structure PssPerformanceCounters
```

**VB Usage**<br />
``` VB Usage
Dim instance As PssPerformanceCounters
```

**C++**<br />
``` C++
public value class PssPerformanceCounters
```

**F#**<br />
``` F#
[<SealedAttribute>]
type PssPerformanceCounters =  struct end
```

The PssPerformanceCounters type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssPerformanceCounters_AuxPagesCycleCount">AuxPagesCycleCount</a></td><td>
The count of clock cycles spent for the capture of auxiliary page information.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssPerformanceCounters_AuxPagesWallClockPeriod">AuxPagesWallClockPeriod</a></td><td>
The count of FILETIME units spent for the capture of auxiliary page information.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssPerformanceCounters_HandlesCycleCount">HandlesCycleCount</a></td><td>
The count of clock cycles spent for the capture of handle information.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssPerformanceCounters_HandlesWallClockPeriod">HandlesWallClockPeriod</a></td><td>
The count of FILETIME units spent for the capture of handle information.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssPerformanceCounters_ThreadsCycleCount">ThreadsCycleCount</a></td><td>
The count of clock cycles spent for the capture of thread information.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssPerformanceCounters_ThreadsWallClockPeriod">ThreadsWallClockPeriod</a></td><td>
The count of FILETIME units spent for the capture of thread information.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssPerformanceCounters_TotalCycleCount">TotalCycleCount</a></td><td>
The count of clock cycles spent for capture.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssPerformanceCounters_TotalWallClockPeriod">TotalWallClockPeriod</a></td><td>
The count of FILETIME units spent for capture.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssPerformanceCounters_VirtualAddressCloneCycleCount">VirtualAddressCloneCycleCount</a></td><td>
The count of clock cycles spent for the capture of the virtual address clone.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssPerformanceCounters_VirtualAddressCloneWallClockPeriod">VirtualAddressCloneWallClockPeriod</a></td><td>
The count of FILETIME units spent for the capture of the virtual address clone.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssPerformanceCounters_VirtualAddressSpaceCycleCount">VirtualAddressSpaceCycleCount</a></td><td>
The count of clock cycles spent for the capture of virtual address space information.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PssPerformanceCounters_VirtualAddressSpaceWallClockPeriod">VirtualAddressSpaceWallClockPeriod</a></td><td>
The count of FILETIME units spent for the capture virtual address space information.</td></tr></table>&nbsp;
<a href="#pssperformancecounters-structure">Back to Top</a>

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
<a href="#pssperformancecounters-structure">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/desktop/api/processsnapshot/ns-processsnapshot-pss_performance_counters" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/desktop/api/processsnapshot/ns-processsnapshot-pss_performance_counters</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />