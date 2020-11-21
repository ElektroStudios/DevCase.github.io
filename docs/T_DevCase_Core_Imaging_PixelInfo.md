# PixelInfo Class
 

Represents pixel information relative to an image.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Imaging.PixelInfo<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("PixelInfo")]
public sealed class PixelInfo : AestheticObject, 
	ISerializable
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("PixelInfo")>
Public NotInheritable Class PixelInfo
	Inherits AestheticObject
	Implements ISerializable
```

**VB Usage**<br />
``` VB Usage
Dim instance As PixelInfo
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"PixelInfo")]
public ref class PixelInfo sealed : public AestheticObject, 
	ISerializable
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("PixelInfo")>]
type PixelInfo =  
    class
        inherit AestheticObject
        interface ISerializable
    end
```

The PixelInfo type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_PixelInfo__ctor">PixelInfo(Color, Int32, Point)</a></td><td>
Initializes a new instance of the PixelInfo class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_PixelInfo__ctor_1">PixelInfo(Pen, Int32, Point)</a></td><td>
Initializes a new instance of the PixelInfo class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_PixelInfo__ctor_2">PixelInfo(SolidBrush, Int32, Point)</a></td><td>
Initializes a new instance of the PixelInfo class.</td></tr></table>&nbsp;
<a href="#pixelinfo-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_PixelInfo_Color">Color</a></td><td>
Gets the <a href="P_DevCase_Core_Imaging_PixelInfo_Color">Color</a> of the pixel.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_PixelInfo_Location">Location</a></td><td>
Gets the location coordinates of the pixel relative to the image.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_PixelInfo_Position">Position</a></td><td>
Gets the position index of the pixel in the image.</td></tr></table>&nbsp;
<a href="#pixelinfo-class">Back to Top</a>

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
<a href="#pixelinfo-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />