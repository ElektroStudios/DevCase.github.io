# SymbolInfo Structure
 

Contains information about a symbol.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct SymbolInfo
```

**VB**<br />
``` VB
Public Structure SymbolInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As SymbolInfo
```

**C++**<br />
``` C++
public value class SymbolInfo
```

**F#**<br />
``` F#
[<SealedAttribute>]
type SymbolInfo =  struct end
```

The SymbolInfo type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo__ctor">SymbolInfo</a></td><td>
Initializes a new instance of the SymbolInfo structure.</td></tr></table>&nbsp;
<a href="#symbolinfo-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_Address">Address</a></td><td>
The virtual address of the start of the symbol.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_Flags">Flags</a></td><td>
The symbol information. 

 This member can be one or more of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SymFlags">SymFlags</a> values.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_Index">Index</a></td><td>
The unique value for the symbol. 

 The value associated with a symbol is not guaranteed to be the same each time you run the process. 

 For `.pbd` symbols, the index value for a symbol is not generated until the symbol is enumerated or retrieved through a search by name or address. 

 The index values for all CodeView and `COFF` symbols are generated when the symbols are loaded.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_MaxNameLen">MaxNameLen</a></td><td>
The size of the Name buffer, in characters. 

 If this member is 0, the Name member is not used.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_ModBase">ModBase</a></td><td>
The base address of the module that contains the symbol.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_Name">Name</a></td><td>
The name of the symbol. 

 The name can be undecorated if the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SymOptionFlags">UndName</a> option is used with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SymSetOptions">SymSetOptions(SymOptionFlags)</a> function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_NameLen">NameLen</a></td><td>
The length of the name, in characters, not including the null-terminating character.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_Register">Register</a></td><td>
The register.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_Reserved1">Reserved1</a></td><td>
This member is reserved for system use.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_Reserved2">Reserved2</a></td><td>
This member is reserved for system use.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_Scope">Scope</a></td><td>
The `DIA` scope.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_Size">Size</a></td><td>
The symbol size, in bytes. 

 This value is meaningful only if the module symbols are from a pdb file; otherwise, this value is typically zero and should be ignored.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_SizeOfStruct">SizeOfStruct</a></td><td>
The size of this structure, In bytes. 

 Set this member to `Marshal.SizeOf(Of SymbolInfo)` before calling any function. 

 Note that the total size of the data is the `SizeOfStruct + (MaxNameLen - 1) * Marshal.SizeOf(Char)`. 

 The reason to subtract one is that the first character in the name is accounted for in the size of the structure.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_Tag">Tag</a></td><td>
The `PDB` classification.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_TypeIndex">TypeIndex</a></td><td>
A unique value that identifies the type data that describes the symbol. 

 This value does not persist between sessions.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_Value">Value</a></td><td>
The value of a constant.</td></tr></table>&nbsp;
<a href="#symbolinfo-structure">Back to Top</a>

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
<a href="#symbolinfo-structure">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms680686%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms680686%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />