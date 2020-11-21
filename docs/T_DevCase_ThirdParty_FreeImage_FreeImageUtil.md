# FreeImageUtil Class
 

Contains FreeImage related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.FreeImage.FreeImageUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class FreeImageUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class FreeImageUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As FreeImageUtil
```

**C++**<br />
``` C++
public ref class FreeImageUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type FreeImageUtil =  
    class
        inherit AestheticObject
    end
```

The FreeImageUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_FreeImage_FreeImageUtil_Version">Version</a></td><td>
Gets the `FreeImage.dll` file version.</td></tr></table>&nbsp;
<a href="#freeimageutil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_FreeImage_FreeImageUtil_Convert">Convert(Bitmap, String, FREE_IMAGE_FORMAT, FREE_IMAGE_SAVE_FLAGS)</a></td><td>
Converts the format of the specified image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_FreeImage_FreeImageUtil_Convert_1">Convert(String, String, FREE_IMAGE_FORMAT, FREE_IMAGE_SAVE_FLAGS)</a></td><td>
Converts the format of the specified image file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_FreeImage_FreeImageUtil_GetFormat">GetFormat</a></td><td>
Gets the format of the specified image file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_FreeImage_FreeImageUtil_GetThumbnail">GetThumbnail(Bitmap, Int32, Boolean)</a></td><td>
Generates a thumbnail from the specified image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_FreeImage_FreeImageUtil_GetThumbnail_1">GetThumbnail(String, Int32, Boolean)</a></td><td>
Generates a thumbnail from the specified image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_FreeImage_FreeImageUtil_GrayScale">GrayScale(Bitmap)</a></td><td>
Grayscales the specified image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_FreeImage_FreeImageUtil_GrayScale_1">GrayScale(String)</a></td><td>
Grayscales the specified image file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_FreeImage_FreeImageUtil_Resize">Resize(Bitmap, Size, FREE_IMAGE_FILTER)</a></td><td>
Resizes the specified image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_FreeImage_FreeImageUtil_Resize_2">Resize(String, Size, FREE_IMAGE_FILTER)</a></td><td>
Resizes the specified image file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_FreeImage_FreeImageUtil_Resize_1">Resize(Bitmap, Int32, Int32, FREE_IMAGE_FILTER)</a></td><td>
Resizes the specified image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_FreeImage_FreeImageUtil_Resize_3">Resize(String, Int32, Int32, FREE_IMAGE_FILTER)</a></td><td>
Resizes the specified image file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_FreeImage_FreeImageUtil_Rotate">Rotate(Bitmap, Double)</a></td><td>
Rotates the specified image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_FreeImage_FreeImageUtil_Rotate_1">Rotate(String, Double)</a></td><td>
Rotates the specified image.</td></tr></table>&nbsp;
<a href="#freeimageutil-class">Back to Top</a>

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
<a href="#freeimageutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage Namespace</a><br />