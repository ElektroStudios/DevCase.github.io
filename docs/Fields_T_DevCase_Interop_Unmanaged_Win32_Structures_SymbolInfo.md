# SymbolInfo Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo">SymbolInfo</a> type exposes the following members.


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
<a href="#symbolinfo-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo">SymbolInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />