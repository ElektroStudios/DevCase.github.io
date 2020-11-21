# BBCodeNode Class
 

Represents a BBCode node.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.NET.BBCodeNode<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_NET_BBCodeDocument">DevCase.Core.NET.BBCodeDocument</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_NET_BBCodeTextNode">DevCase.Core.NET.BBCodeTextNode</a><br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class BBCodeNode : AestheticObject
```

**VB**<br />
``` VB
Public Class BBCodeNode
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As BBCodeNode
```

**C++**<br />
``` C++
public ref class BBCodeNode : public AestheticObject
```

**F#**<br />
``` F#
type BBCodeNode =  
    class
        inherit AestheticObject
    end
```

The BBCodeNode type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeNode__ctor">BBCodeNode(String)</a></td><td>
Initializes a new instance of the BBCodeNode class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeNode__ctor_1">BBCodeNode(String, String)</a></td><td>
Initializes a new instance of the BBCodeNode class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeNode__ctor_2">BBCodeNode(String, String, Boolean)</a></td><td>
Initializes a new instance of the BBCodeNode class.</td></tr></table>&nbsp;
<a href="#bbcodenode-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_BBCodeNode_Attribute">Attribute</a></td><td>
Gets or sets this node's attribute. 

 The Attribute is the part of the tag that comes after the equals sign. 

 It is optional, and this property may return either null or an empty string.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_BBCodeNode_Children">Children</a></td><td>
Gets an array of this node's child nodes</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_BBCodeNode_Item">Item(Int32)</a></td><td>
Gets the child BBCodeNode.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_BBCodeNode_Item_1">Item(String)</a></td><td>
Gets an array of children BBCodeNode with the specified TagName</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_BBCodeNode_Parent">Parent</a></td><td>
Gets the parent node of this node.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_BBCodeNode_Singular">Singular</a></td><td>
Gets a value indicating whether this node is singular. 

 Singular nodes are self closing and can have no children.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_BBCodeNode_TagName">TagName</a></td><td>
Gets the tag name of this node. 

 The tag name is the main part of the tag, and is mandatory.</td></tr></table>&nbsp;
<a href="#bbcodenode-class">Back to Top</a>

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
<a href="#bbcodenode-class">Back to Top</a>

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
Converts a BBCodeNode to HTML.
 (Defined by <a href="T_DevCase_Core_Extensions_BBCode_BBCodeExtensions">BBCodeExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_BBCode_BBCodeExtensions_ToHtml_1">ToHtml(Boolean)</a></td><td>Overloaded.  
Converts a BBCodeNode to HTML
 (Defined by <a href="T_DevCase_Core_Extensions_BBCode_BBCodeExtensions">BBCodeExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_BBCode_BBCodeExtensions_ToHtml_2">ToHtml(Boolean, Dictionary(String, BBCodeHtmlRenderer.BBCodeHtmlRendererCallback))</a></td><td>Overloaded.  
Converts a BBCodeNode to HTML
 (Defined by <a href="T_DevCase_Core_Extensions_BBCode_BBCodeExtensions">BBCodeExtensions</a>.)</td></tr></table>&nbsp;
<a href="#bbcodenode-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />