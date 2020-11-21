# ReparseDataBuffer Structure
 

Contains reparse point data for a Microsoft reparse point.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct ReparseDataBuffer
```

**VB**<br />
``` VB
Public Structure ReparseDataBuffer
```

**VB Usage**<br />
``` VB Usage
Dim instance As ReparseDataBuffer
```

**C++**<br />
``` C++
public value class ReparseDataBuffer
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ReparseDataBuffer =  struct end
```

The ReparseDataBuffer type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_Buffer">Buffer</a></td><td>
A buffer that contains the Unicode strings for the substitute name and the print name, as described by <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_SubstituteNameOffset">SubstituteNameOffset</a>, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_SubstituteNameLength">SubstituteNameLength</a>, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_PrintNameOffset">PrintNameOffset</a>, and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_PrintNameLength">PrintNameLength</a>. 

 The substitute name string MUST be a Unicode path to the target of the symbolic link. 

 The print name string MUST be a Unicode string, suitable for display to a user, that also identifies the target of the symbolic link.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_Flags">Flags</a></td><td>
Flags that pecifies whether the substitute is an absolute target path name or a path name relative to the directory containing the symbolic link.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_PrintNameLength">PrintNameLength</a></td><td>
The length, in bytes, of the print name string. 

 If there is a terminating null character at the end of the string, it is not included in the PrintNameLength count. 

 This value MUST be greater than or equal to 0.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_PrintNameOffset">PrintNameOffset</a></td><td>
The offset, in bytes, from the beginning of the PathBuffer field, at which the print name is located. 

 The print name is the user-friendly name the client MUST return to the application if it requests the name of the symbolic link target</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_ReparseDataLength">ReparseDataLength</a></td><td>
Size, in bytes, of the reparse data in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_Buffer">Buffer</a> member.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_ReparseTag">ReparseTag</a></td><td>
Reparse point tag. Must be a Microsoft reparse point tag.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_Reserved">Reserved</a></td><td>
Length, in bytes, of the unparsed portion of the file name pointed to by the FileName member of the associated file object. 

 This member is only valid for create operations when the I/O fails with STATUS_REPARSE. For all other purposes, such as setting or querying a reparse point for the reparse data, this member is treated as reserved.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_SubstituteNameLength">SubstituteNameLength</a></td><td>
The length, in bytes, of the substitute name string. 

 If there is a terminating null character at the end of the string, it is not included in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_SubstituteNameLength">SubstituteNameLength</a> count. 

 This value MUST be greater than or equal to 0.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_SubstituteNameOffset">SubstituteNameOffset</a></td><td>
The offset, in bytes, from the beginning of the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_Buffer">Buffer</a> member, at which the substitute name is located. 

 The substitute name is the name the client MUST use to access this file if it requires to follow the symbolic link.</td></tr></table>&nbsp;
<a href="#reparsedatabuffer-structure">Back to Top</a>

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
<a href="#reparsedatabuffer-structure">Back to Top</a>

## Remarks
Reparse points: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/aa365503%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/aa365503%28v=vs.85%29.aspx</a>

 _REPARSE_DATA_BUFFER structure: <a href="https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/ntifs/ns-ntifs-_reparse_data_buffer" target="_blank">https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/ntifs/ns-ntifs-_reparse_data_buffer</a>

 Symbolic Link Error Response: <a href="https://msdn.microsoft.com/en-us/library/cc246542.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/cc246542.aspx</a>

 Credits: 

<a href="http://troyparsons.com/blog/2012/03/symbolic-links-in-c-sharp/" target="_blank">http://troyparsons.com/blog/2012/03/symbolic-links-in-c-sharp/</a> and <a href="http://www.pinvoke.net/default.aspx/Structures.REPARSE_DATA_BUFFER" target="_blank">http://www.pinvoke.net/default.aspx/Structures.REPARSE_DATA_BUFFER</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />