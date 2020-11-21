# BBCodeNode Methods
 

The <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a> type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeNode_AppendChild_1">AppendChild(String)</a></td><td>
Adds a new child node at the end of this node's descendants.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeNode_AppendChild">AppendChild(BBCodeNode)</a></td><td>
Adds a new child node at the end of this node's descendants.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeNode_AppendChild_2">AppendChild(String, String)</a></td><td>
Adds a new child node at the end of this node's descendants</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeNode_Clone">Clone</a></td><td>
Creates a recursive copy of the current nodes and its children.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeNode_InsertAfter">InsertAfter</a></td><td>
Inserts a new child node after the reference node passed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeNode_InsertBefore">InsertBefore</a></td><td>
Inserts a new child node before the reference node passed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeNode_PrependChild">PrependChild</a></td><td>
Adds a new child node at the beginning of this node's descendants.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeNode_RemoveAll">RemoveAll</a></td><td>
Removes all child nodes.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeNode_RemoveChild">RemoveChild</a></td><td>
Removes a specific child node.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeNode_ReplaceChild">ReplaceChild</a></td><td>
Replaces a specific child node with another.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeNode_ToString">ToString</a></td><td>
Recursively generates the BBCode representation of the current node and its children.
 (Overrides AestheticObject.ToString().)</td></tr></table>&nbsp;
<a href="#bbcodenode-methods">Back to Top</a>

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
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_BBCode_BBCodeExtensions_ToHtml">ToHtml()</a></td><td>Overloaded.  
Converts a <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a> to HTML.
 (Defined by <a href="T_DevCase_Core_Extensions_BBCode_BBCodeExtensions">BBCodeExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_BBCode_BBCodeExtensions_ToHtml_1">ToHtml(Boolean)</a></td><td>Overloaded.  
Converts a <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a> to HTML
 (Defined by <a href="T_DevCase_Core_Extensions_BBCode_BBCodeExtensions">BBCodeExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_BBCode_BBCodeExtensions_ToHtml_2">ToHtml(Boolean, Dictionary(String, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback))</a></td><td>Overloaded.  
Converts a <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a> to HTML
 (Defined by <a href="T_DevCase_Core_Extensions_BBCode_BBCodeExtensions">BBCodeExtensions</a>.)</td></tr></table>&nbsp;
<a href="#bbcodenode-methods">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />