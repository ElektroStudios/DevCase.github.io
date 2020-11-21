# MemoryStatusEx Structure
 

contains information about the current state of both physical and virtual memory, including extended memory.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct MemoryStatusEx
```

**VB**<br />
``` VB
Public Structure MemoryStatusEx
```

**VB Usage**<br />
``` VB Usage
Dim instance As MemoryStatusEx
```

**C++**<br />
``` C++
public value class MemoryStatusEx
```

**F#**<br />
``` F#
[<SealedAttribute>]
type MemoryStatusEx =  struct end
```

The MemoryStatusEx type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx__ctor">MemoryStatusEx</a></td><td>
Initializes a new instance of the MemoryStatusEx structure.</td></tr></table>&nbsp;
<a href="#memorystatusex-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_ExtendedVirtualAvailable">ExtendedVirtualAvailable</a></td><td>
Size of unreserved and uncommitted memory in the extended portion of the virtual address space of the calling process, in bytes.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_MemoryLoad">MemoryLoad</a></td><td>
Number between 0 and 100 that specifies the approximate percentage of physical memory that is in use 

 (0 indicates no memory use and 100 indicates full memory use).</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_PageFileAvailable">PageFileAvailable</a></td><td>
Size of available memory to commit, in bytes. 

 The limit is <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_PageFileTotal">PageFileTotal</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_PageFileTotal">PageFileTotal</a></td><td>
Size of the committed memory limit, in bytes. 

 This is physical memory plus the size of the page file, minus a small overhead.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_PhysicalAvailable">PhysicalAvailable</a></td><td>
Size of physical memory available, in bytes.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_PhysicalTotal">PhysicalTotal</a></td><td>
Total size of physical memory, in bytes.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_SizeOfStruct">SizeOfStruct</a></td><td>
The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of MemoryStatusEx)` before calling any function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_VirtualAvailable">VirtualAvailable</a></td><td>
Size of unreserved and uncommitted memory in the user mode portion of the virtual address space of the calling process, in bytes.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx_VirtualTotal">VirtualTotal</a></td><td>
Total size of the user mode portion of the virtual address space of the calling process, in bytes.</td></tr></table>&nbsp;
<a href="#memorystatusex-structure">Back to Top</a>

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
<a href="#memorystatusex-structure">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/ns-sysinfoapi-_memorystatusex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/ns-sysinfoapi-_memorystatusex</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />