# BBCodeDocument Class
 

Represents an entire BBCode document. Similar to the HTML tag <body>


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_NET_BBCodeNode">DevCase.Core.NET.BBCodeNode</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.NET.BBCodeDocument<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class BBCodeDocument : BBCodeNode
```

**VB**<br />
``` VB
Public NotInheritable Class BBCodeDocument
	Inherits BBCodeNode
```

**VB Usage**<br />
``` VB Usage
Dim instance As BBCodeDocument
```

**C++**<br />
``` C++
public ref class BBCodeDocument sealed : public BBCodeNode
```

**F#**<br />
``` F#
[<SealedAttribute>]
type BBCodeDocument =  
    class
        inherit BBCodeNode
    end
```

The BBCodeDocument type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_BBCodeDocument__ctor">BBCodeDocument</a></td><td>
Initializes a new instance of the BBCodeDocument class.</td></tr></table>&nbsp;
<a href="#bbcodedocument-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_NET_BBCodeDocument_Load">Load(String)</a></td><td>
Loads a string of BBCode as a BBCodeDocument object</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_NET_BBCodeDocument_Load_1">Load(String, Boolean)</a></td><td>
Loads a string of BBCode as a BBCodeDocument object</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_NET_BBCodeDocument_Load_2">Load(String, Boolean, IEnumerable(String))</a></td><td>
Loads a string of BBCode as a BBCodeDocument object</td></tr></table>&nbsp;
<a href="#bbcodedocument-class">Back to Top</a>

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
<a href="#bbcodedocument-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />