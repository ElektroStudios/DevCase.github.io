# BBCodeTextNode Class
 

Represents an entire BBCode text node.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_NET_BBCodeNode">DevCase.Core.NET.BBCodeNode</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.NET.BBCodeTextNode<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class BBCodeTextNode : BBCodeNode
```

**VB**<br />
``` VB
Public NotInheritable Class BBCodeTextNode
	Inherits BBCodeNode
```

**VB Usage**<br />
``` VB Usage
Dim instance As BBCodeTextNode
```

**C++**<br />
``` C++
public ref class BBCodeTextNode sealed : public BBCodeNode
```

**F#**<br />
``` F#
[<SealedAttribute>]
type BBCodeTextNode =  
    class
        inherit BBCodeNode
    end
```

The BBCodeTextNode type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeTextNode__ctor">BBCodeTextNode()</a></td><td>
Initializes a new instance of the BBCodeTextNode class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeTextNode__ctor_1">BBCodeTextNode(String)</a></td><td>
Initializes a new instance of the BBCodeTextNode class.</td></tr></table>&nbsp;
<a href="#bbcodetextnode-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_BBCodeTextNode_InnerText">InnerText</a></td><td>
Gets or sets the inner text.</td></tr></table>&nbsp;
<a href="#bbcodetextnode-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeTextNode_AppendChar">AppendChar</a></td><td>
Appends a character to the inner text.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeTextNode_AppendText">AppendText</a></td><td>
Appends a string to the inner text.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeTextNode_ToString">ToString</a></td><td>
Returns a String that represents this BBCodeTextNode.
 (Overrides <a href="M_DevCase_Core_NET_BBCodeNode_ToString">BBCodeNode.ToString()</a>.)</td></tr></table>&nbsp;
<a href="#bbcodetextnode-class">Back to Top</a>

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
<a href="#bbcodetextnode-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />