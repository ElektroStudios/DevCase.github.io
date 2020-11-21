# ObjectHandleAttributes Enumeration
 

Specifies flags for the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_Attributes">Attributes</a> field.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ObjectHandleAttributes
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ObjectHandleAttributes
```

**VB Usage**<br />
``` VB Usage
Dim instance As ObjectHandleAttributes
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ObjectHandleAttributes
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ObjectHandleAttributes
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ObjectHandleAttributes.Inherit">**Inherit**</td><td>2</td><td>This handle can be inherited by child processes of the current process.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ObjectHandleAttributes.Permanent">**Permanent**</td><td>16</td><td>This flag only applies to objects that are named within the object manager. By default, such objects are deleted when all open handles to them are closed. 

 If this flag is specified, the object is not deleted when all open handles are closed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ObjectHandleAttributes.Exclusive">**Exclusive**</td><td>32</td><td>If this flag is set and the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes">ObjectAttributes</a> structure is passed to a routine that creates an object, the object can be accessed exclusively. That is, once a process opens such a handle to the object, no other processes can open handles to this object. 

 If this flag is set and the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes">ObjectAttributes</a> structure is passed to a routine that creates an object handle, the caller is requesting exclusive access to the object for the process context that the handle was created in. This request can be granted only if the Exclusive flag was set when the object was created.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ObjectHandleAttributes.CaseInsensitive">**CaseInsensitive**</td><td>64</td><td>If this flag is specified, a case-insensitive comparison is used when matching the name pointed to by the <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_ObjectName">ObjectName</a> member against the names of existing objects. 

 Otherwise, object names are compared using the default system settings.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ObjectHandleAttributes.OpenIf">**OpenIf**</td><td>128</td><td>If this flag is specified, by using the object handle, to a routine that creates objects and if that object already exists, the routine should open that object. 

 Otherwise, the routine creating the object returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">OBJECT_NAME_COLLISION</a> error code.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ObjectHandleAttributes.OpenLink">**OpenLink**</td><td>256</td><td>If an object handle, with this flag set, is passed to a routine that opens objects and if the object is a symbolic link object, the routine should open the symbolic link object itself, rather than the object that the symbolic link refers to (which is the default behavior).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ObjectHandleAttributes.KernelHandle">**KernelHandle**</td><td>512</td><td>The handle is created in system process context and can only be accessed from kernel mode.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ObjectHandleAttributes.ForceAccessCheck">**ForceAccessCheck**</td><td>1024</td><td>The routine that opens the handle should enforce all access checks for the object, even if the handle is being opened in kernel mode.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ObjectHandleAttributes.ValidAttributes">**ValidAttributes**</td><td>2034</td><td>The mask of all valid attributes.</td></tr></table>

## Remarks
<a href="https://technet.microsoft.com/es-es/ff557749(v=vs.71)" target="_blank">https://technet.microsoft.com/es-es/ff557749(v=vs.71)</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />