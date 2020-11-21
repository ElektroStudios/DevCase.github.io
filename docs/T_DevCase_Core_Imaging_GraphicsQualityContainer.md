# GraphicsQualityContainer Class
 

An Object that encapsulates GDI+ properties to represent in a friendlly way the overall quality of graphics.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Imaging.GraphicsQualityContainer<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("GraphicsQualityContainer")]
public class GraphicsQualityContainer : AestheticObject
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("GraphicsQualityContainer")>
Public Class GraphicsQualityContainer
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As GraphicsQualityContainer
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"GraphicsQualityContainer")]
public ref class GraphicsQualityContainer : public AestheticObject
```

**F#**<br />
``` F#
[<SerializableAttribute>]
[<XmlRootAttribute("GraphicsQualityContainer")>]
type GraphicsQualityContainer =  
    class
        inherit AestheticObject
    end
```

The GraphicsQualityContainer type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_GraphicsQualityContainer__ctor">GraphicsQualityContainer</a></td><td>
Initializes a new instance of the GraphicsQualityContainer class.</td></tr></table>&nbsp;
<a href="#graphicsqualitycontainer-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_GraphicsQualityContainer_CompositingQuality">CompositingQuality</a></td><td>
Gets or sets the quality level to use during compositing.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_GraphicsQualityContainer_InterpolationMode">InterpolationMode</a></td><td>
Gets or sets the algorithm that is used when images are scaled or rotated.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_GraphicsQualityContainer_PixelOffsetMode">PixelOffsetMode</a></td><td>
Gets or sets a value that indicates how pixels are offset during rendering.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_GraphicsQualityContainer_QualityMode">QualityMode</a></td><td>
Gets or sets the overall quality when rendering GDI+ objects.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_GraphicsQualityContainer_SmoothingMode">SmoothingMode</a></td><td>
Gets or sets a value that indicates whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_GraphicsQualityContainer_TextRenderingHint">TextRenderingHint</a></td><td>
Gets or sets the quality of text rendering.</td></tr></table>&nbsp;
<a href="#graphicsqualitycontainer-class">Back to Top</a>

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
<a href="#graphicsqualitycontainer-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />