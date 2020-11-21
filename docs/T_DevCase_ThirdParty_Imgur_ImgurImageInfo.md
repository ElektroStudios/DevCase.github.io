# ImgurImageInfo Class
 

Represents the urls of a Imgur's image.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.Imgur.ImgurImageInfo<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Imgur">DevCase.ThirdParty.Imgur</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ImgurImageInfo : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class ImgurImageInfo
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As ImgurImageInfo
```

**C++**<br />
``` C++
public ref class ImgurImageInfo sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ImgurImageInfo =  
    class
        inherit AestheticObject
    end
```

The ImgurImageInfo type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Imgur_ImgurImageInfo__ctor">ImgurImageInfo(String)</a></td><td>
Initializes a new instance of the ImgurImageInfo class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Imgur_ImgurImageInfo__ctor_1">ImgurImageInfo(Uri)</a></td><td>
Initializes a new instance of the ImgurImageInfo class.</td></tr></table>&nbsp;
<a href="#imgurimageinfo-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Imgur_ImgurImageInfo_Normal">Normal</a></td><td>
Gets the url to the image at normal size.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Imgur_ImgurImageInfo_ThumbnailHuge">ThumbnailHuge</a></td><td>
Gets the url to the image resized to `1024x1024` without preserving image proportions.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Imgur_ImgurImageInfo_ThumbnailLarge">ThumbnailLarge</a></td><td>
Gets the url to the image resized to `640x640` without preserving image proportions.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Imgur_ImgurImageInfo_ThumbnailMedium">ThumbnailMedium</a></td><td>
Gets the url to the image resized to `320x320` without preserving image proportions.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Imgur_ImgurImageInfo_ThumbnailSmall">ThumbnailSmall</a></td><td>
Gets the url to the image resized to `160x160` preserving image proportions.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Imgur_ImgurImageInfo_ThumbnailSquareBig">ThumbnailSquareBig</a></td><td>
Gets the url to the image resized to `160x160` without preserving image proportions.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Imgur_ImgurImageInfo_ThumbnailSquareSmall">ThumbnailSquareSmall</a></td><td>
Gets the url to the image resized to `90x90` without preserving image proportions.</td></tr></table>&nbsp;
<a href="#imgurimageinfo-class">Back to Top</a>

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
<a href="#imgurimageinfo-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_Imgur">DevCase.ThirdParty.Imgur Namespace</a><br />