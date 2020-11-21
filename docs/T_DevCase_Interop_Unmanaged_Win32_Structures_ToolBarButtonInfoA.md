# ToolBarButtonInfoA Structure
 

Contains or receives information for a specific button in a ToolBar control.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct ToolBarButtonInfoA
```

**VB**<br />
``` VB
Public Structure ToolBarButtonInfoA
```

**VB Usage**<br />
``` VB Usage
Dim instance As ToolBarButtonInfoA
```

**C++**<br />
``` C++
public value class ToolBarButtonInfoA
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ToolBarButtonInfoA =  struct end
```

The ToolBarButtonInfoA type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA__ctor">ToolBarButtonInfoA</a></td><td>
Initializes a new instance of the ToolBarButtonInfoA structure.</td></tr></table>&nbsp;
<a href="#toolbarbuttoninfoa-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_ButtonWidth">ButtonWidth</a></td><td>
Width of the button, in pixels.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_CommandId">CommandId</a></td><td>
Command identifier of the button.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_ImageIndex">ImageIndex</a></td><td>
Image index of the button. 

 Set this member to `I_IMAGECALLBACK`, and the toolbar will send the `TBN_GETDISPINFO` notification code to retrieve the image index when it is needed.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_lParam">lParam</a></td><td>
Application-defined value associated with the button</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_Mask">Mask</a></td><td>
Set of flags that indicate which members contain valid information.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_SizeOfStruct">SizeOfStruct</a></td><td>
The size of this structure, In bytes. 

 Set this member to `Marshal.SizeOf(Of ToolBarButtonInfoA)` before calling any function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_State">State</a></td><td>
State flags of the button.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_Style">Style</a></td><td>
Style flags of the button.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_Text">Text</a></td><td>
Address of a character buffer that contains or receives the button text.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_TextSize">TextSize</a></td><td>
Size of the buffer at <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_Text">Text</a> field. 

 If the button information is being set, this member is ignored.</td></tr></table>&nbsp;
<a href="#toolbarbuttoninfoa-structure">Back to Top</a>

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
<a href="#toolbarbuttoninfoa-structure">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb760478%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb760478%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />