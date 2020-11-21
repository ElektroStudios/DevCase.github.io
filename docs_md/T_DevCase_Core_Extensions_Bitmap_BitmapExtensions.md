# BitmapExtensions Class
 

Contains custom extension methods to use with Bitmap type.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.Extensions.Bitmap.BitmapExtensions<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[HideModuleNameAttribute]
public sealed class BitmapExtensions
```

**VB**<br />
``` VB
<ExtensionAttribute>
<HideModuleNameAttribute>
Public NotInheritable Class BitmapExtensions
```

**VB Usage**<br />
``` VB Usage
Dim instance As BitmapExtensions
```

**C++**<br />
``` C++
[ExtensionAttribute]
[HideModuleNameAttribute]
public ref class BitmapExtensions sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ExtensionAttribute>]
[<HideModuleNameAttribute>]
type BitmapExtensions =  class end
```

The BitmapExtensions type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ApplyColorMatrix">ApplyColorMatrix(Bitmap, ColorMatrix)</a></td><td>
Applies a custom color matrix to an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ApplyColorMatrix_1">ApplyColorMatrix(Bitmap, ColorMatrix, GraphicsQualityContainer)</a></td><td>
Applies a custom color matrix to an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Center">Center(Bitmap, Size, GraphicsQualityContainer)</a></td><td>
Centers the source Bitmap within the specified canvas size. 

 The resulting effect is equal than using Center in a PictureBox.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Center_1">Center(Bitmap, Size, GraphicsQualityContainer, Color)</a></td><td>
Centers the source Bitmap within the specified canvas size. 

 The resulting effect is equal than using Center in a PictureBox.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ComputeHash__1">ComputeHash(T)</a></td><td>
Computes a hash code for the source Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ConvertToPixelFormat">ConvertToPixelFormat</a></td><td>
Converts the piel format of the source Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Crop_1">Crop(Bitmap, Rectangle)</a></td><td>
Crops an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Crop">Crop(Bitmap, Point, Size)</a></td><td>
Crops an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Crop_2">Crop(Bitmap, Int32, Int32, Int32, Int32)</a></td><td>
Crops a Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Flip">Flip</a></td><td>
Flips a Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_GetPixelInfo">GetPixelInfo</a></td><td>
For each pixel in the source image, gets the Color, pixel position, and coordinates location respectivelly to the image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_GetPixelInfoAt">GetPixelInfoAt</a></td><td>
Gets a <a href="T_DevCase_Core_Imaging_PixelInfo">PixelInfo</a> instance that contains the Color, pixel position, and coordinates location respectivelly to the image, of the pixel at the specified pixel position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_GetRegion">GetRegion</a></td><td>
Gets a region from the specified Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_GetRegionExclude">GetRegionExclude</a></td><td>
Gets a reversed region from the specified Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_GetRegionInclude">GetRegionInclude</a></td><td>
Gets a region from the specified Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_GetRegionReverse">GetRegionReverse</a></td><td>
Gets a reversed region from the specified Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_InvertColors">InvertColors(Bitmap)</a></td><td>
Inverts the colors of an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_InvertColors_1">InvertColors(Bitmap, GraphicsQualityContainer)</a></td><td>
Inverts the colors of an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ReplaceColor">ReplaceColor</a></td><td>
Replaces the specified color in a Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Resize">Resize(Bitmap, Double, Boolean)</a></td><td>
Resizes an Bitmap by the given percentage.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Resize_2">Resize(Bitmap, Size, Boolean)</a></td><td>
Resizes an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Resize_1">Resize(Bitmap, Double, Boolean, GraphicsQualityContainer)</a></td><td>
Resizes an Bitmap by the given percentage.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Resize_3">Resize(Bitmap, Size, Boolean, GraphicsQualityContainer)</a></td><td>
Resizes an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Scale">Scale(Bitmap, Single)</a></td><td>
Scales an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Scale_1">Scale(Bitmap, Single, GraphicsQualityContainer)</a></td><td>
Scales an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_SetBrightness">SetBrightness(Bitmap, Single)</a></td><td>
Adjusts the brightness of an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_SetBrightness_1">SetBrightness(Bitmap, Single, GraphicsQualityContainer)</a></td><td>
Adjusts the brightness of an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_SetContrast">SetContrast(Bitmap, Single)</a></td><td>
Adjusts the contrast of an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_SetContrast_1">SetContrast(Bitmap, Single, GraphicsQualityContainer)</a></td><td>
Adjusts the contrast of an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_SetGamma">SetGamma(Bitmap, Single)</a></td><td>
Adjusts the gamma of an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_SetGamma_1">SetGamma(Bitmap, Single, GraphicsQualityContainer)</a></td><td>
Adjusts the gamma of an Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_SetOpacity">SetOpacity(Bitmap, Single)</a></td><td>
Sets the opacity of a Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_SetOpacity_1">SetOpacity(Bitmap, Single, GraphicsQualityContainer)</a></td><td>
Sets the opacity of a Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Stretch">Stretch</a></td><td>
Stretches the source Bitmap within the specified canvas size. 

 The resulting effect is equal than using Stretch for BackgroundImageLayout property.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Tile">Tile</a></td><td>
Tiles the source Bitmap accross the specified canvas size. 

 The resulting effect is equal than using Tile in a PictureBox.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ToArray">ToArray</a></td><td>
Converts an Bitmap to a Byte array.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ToBase64">ToBase64</a></td><td>
Converts the source image to a Base64 encoded string.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ToBitmapFrame">ToBitmapFrame</a></td><td>
Converts the source Bitmap to a BitmapFrame.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ToBitmapImage">ToBitmapImage</a></td><td>
Converts the source Bitmap to a BitmapImage.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ToBitmapSource">ToBitmapSource</a></td><td>
Converts the source Bitmap to a BitmapSource.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ToBlackAndWhite">ToBlackAndWhite(Bitmap)</a></td><td>
Transforms a Bitmap to black and white colors.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ToBlackAndWhite_1">ToBlackAndWhite(Bitmap, Single)</a></td><td>
Transforms a Bitmap to black and white colors.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ToBlackAndWhite_2">ToBlackAndWhite(Bitmap, Single, GraphicsQualityContainer)</a></td><td>
Transforms a Bitmap to black and white colors.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ToGrayscale">ToGrayscale(Bitmap, GrayscaleLevel)</a></td><td>
Transforms a Bitmap to grayscale colors.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ToGrayscale_1">ToGrayscale(Bitmap, GrayscaleLevel, GraphicsQualityContainer)</a></td><td>
Transforms a Bitmap to grayscale colors.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ToIcon">ToIcon</a></td><td>
Converts a Bitmap to a Icon.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ToMemoryStream">ToMemoryStream</a></td><td>
Converts an Bitmap to a <a href="N_DevCase_Core_Extensions_MemoryStream">DevCase.Core.Extensions.MemoryStream</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ToRectangle">ToRectangle</a></td><td>
Returns a Rectangle with the width and height of the source Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_ToRectangleF">ToRectangleF</a></td><td>
Returns a RectangleF with the width and height of the source Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Zoom">Zoom(Bitmap, Size, GraphicsQualityContainer)</a></td><td>
Enlarges the source Bitmap within the specified canvas size, preserving its aspect ratio. 

 The resulting effect is equal than using Zoom for BackgroundImageLayout property.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Bitmap_BitmapExtensions_Zoom_1">Zoom(Bitmap, Size, GraphicsQualityContainer, Color)</a></td><td>
Enlarges the source Bitmap within the specified canvas size, preserving its aspect ratio. 

 The resulting effect is equal than using Zoom for BackgroundImageLayout property.</td></tr></table>&nbsp;
<a href="#bitmapextensions-class">Back to Top</a>

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
<a href="#bitmapextensions-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap Namespace</a><br />