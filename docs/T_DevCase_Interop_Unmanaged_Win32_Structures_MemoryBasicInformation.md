# MemoryBasicInformation Structure
 

Contains information about a range of pages in the virtual address space of a process. 

 The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualQuery">VirtualQuery(IntPtr, MemoryBasicInformation, IntPtr)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualQueryEx">VirtualQueryEx(IntPtr, IntPtr, MemoryBasicInformation, IntPtr)</a> functions use this structure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct MemoryBasicInformation
```

**VB**<br />
``` VB
Public Structure MemoryBasicInformation
```

**VB Usage**<br />
``` VB Usage
Dim instance As MemoryBasicInformation
```

**C++**<br />
``` C++
public value class MemoryBasicInformation
```

**F#**<br />
``` F#
[<SealedAttribute>]
type MemoryBasicInformation =  struct end
```

The MemoryBasicInformation type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_AllocationBase">AllocationBase</a></td><td>
A pointer to the base address of a range of pages allocated by the VirtualAlloc function. 

 The page pointed to by the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_BaseAddress">BaseAddress</a> member is contained within this allocation range.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_AllocationProtect">AllocationProtect</a></td><td>
The memory protection option when the region was initially allocated. 

 This member can be one of the memory protection constants or 0 if the caller does not have access.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_BaseAddress">BaseAddress</a></td><td>
A pointer to the base address of the region of pages.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_Protect">Protect</a></td><td>
The access protection of the pages in the region. 

 This member is one of the values listed for the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_AllocationProtect">AllocationProtect</a> member.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_RegionSize">RegionSize</a></td><td>
The size of the region beginning at the base address in which all pages have identical attributes, in bytes.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_State">State</a></td><td>
The state of the pages in the region.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation_Type">Type</a></td><td>
The type of pages in the region.</td></tr></table>&nbsp;
<a href="#memorybasicinformation-structure">Back to Top</a>

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
<a href="#memorybasicinformation-structure">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa366775(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa366775(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />