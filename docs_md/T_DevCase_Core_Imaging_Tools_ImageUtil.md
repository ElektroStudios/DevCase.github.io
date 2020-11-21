# ImageUtil Class
 

Contains image related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Imaging.Tools.ImageUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ImageUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class ImageUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As ImageUtil
```

**C++**<br />
``` C++
public ref class ImageUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ImageUtil =  
    class
        inherit AestheticObject
    end
```

The ImageUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_CaptureCursorIcon">CaptureCursorIcon()</a></td><td>
Captures the mouse cursor icon.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_CaptureCursorIcon_1">CaptureCursorIcon(Point)</a></td><td>
Captures the mouse cursor icon.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_CompressImage">CompressImage(String, ImageFormat, Int32)</a></td><td>
Compresses a image file to the specified filesize and returns the raw image stream of the compressed image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_CompressImage_1">CompressImage(String, String, ImageFormat, Int32)</a></td><td>
Compresses a image file to the specified filesize and saves the compressed image to disk.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_ConvertImageFile_1">ConvertImageFile(String, BitmapEncoder)</a></td><td>
Converts a image file to a different image format and returns the raw image stream of the converted image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_ConvertImageFile">ConvertImageFile(String, String, BitmapEncoder)</a></td><td>
Converts a image file to a different image format and saves the converted image to disk.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_CreateSolidcolorBitmap">CreateSolidcolorBitmap</a></td><td>
Creates a Bitmap image which is filled with the specified solid color.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_ExtractIconFromExecutableFile">ExtractIconFromExecutableFile(String, Int32)</a></td><td>
Extracts a icon stored in the specified executable, dll or icon file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_ExtractIconFromExecutableFile_1">ExtractIconFromExecutableFile(String, Int32, Int32)</a></td><td>
Extracts a icon stored in the specified executable, dll or icon file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_ExtractIconFromFile">ExtractIconFromFile</a></td><td>
Extracts the icon associated for the specified file. 

 Note: the maximum size of the returned icon only can be 32x32.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_ExtractIconFromFileExtension">ExtractIconFromFileExtension</a></td><td>
Extracts the icon associated for the specified file extension. 

 Note: the maximum size of the returned icon only can be 32x32.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_ExtractIconFromFileOrDirectory">ExtractIconFromFileOrDirectory</a></td><td>
Extracts the icon associated for the specified file or directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetDifferences">GetDifferences</a></td><td>
Finds the RGB differences between two images and returns them in a two-dimensional Array.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetFramesFromImage">GetFramesFromImage</a></td><td>
Gets a List(T) containing all the frames in the source GIF image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetGrayScalePixelPercentOfImage">GetGrayScalePixelPercentOfImage(Image)</a></td><td>
Analyzes each pixel of the spcified image, counts all the pixels that are within the grayscale RGB range, then calculates a percentage of the total grayscale presence in the image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetGrayScalePixelPercentOfImage_2">GetGrayScalePixelPercentOfImage(FileInfo)</a></td><td>
Analyzes each pixel of the spcified image, counts all the pixels that are within the grayscale RGB range, then calculates a percentage of the total grayscale presence in the image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetGrayScalePixelPercentOfImage_4">GetGrayScalePixelPercentOfImage(String)</a></td><td>
Analyzes each pixel of the spcified image, counts all the pixels that are within the grayscale RGB range, then calculates a percentage of the total grayscale presence in the image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetGrayScalePixelPercentOfImage_1">GetGrayScalePixelPercentOfImage(Image, Int32)</a></td><td>
Analyzes each pixel of the spcified image, counts all the pixels that are within the grayscale RGB range, then calculates a percentage of the total grayscale presence in the image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetGrayScalePixelPercentOfImage_3">GetGrayScalePixelPercentOfImage(FileInfo, Int32)</a></td><td>
Analyzes each pixel of the spcified image, counts all the pixels that are within the grayscale RGB range, then calculates a percentage of the total grayscale presence in the image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetGrayScalePixelPercentOfImage_5">GetGrayScalePixelPercentOfImage(String, Int32)</a></td><td>
Analyzes each pixel of the spcified image, counts all the pixels that are within the grayscale RGB range, then calculates a percentage of the total grayscale presence in the image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetIconCountFromExecutableFile">GetIconCountFromExecutableFile</a></td><td>
Gets the total amount of icons stored in the specified executable, dll or icon file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetPercentageDifference">GetPercentageDifference(Image, Image, Byte)</a></td><td>
Gets a value indicating the percentage of difference between two images.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetPercentageDifference_1">GetPercentageDifference(String, String, Byte)</a></td><td>
Gets a value indicating the percentage of difference between two images.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetPixelColorPercentOfImage">GetPixelColorPercentOfImage(Image, Color)</a></td><td>
Analyzes each pixel of the spcified image, counts all the pixels that are of same color as the color specified, then calculates a percentage of the total grayscale presence in the image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetPixelColorPercentOfImage_2">GetPixelColorPercentOfImage(FileInfo, Color)</a></td><td>
Analyzes each pixel of the spcified image, counts all the pixels that are of same color as the color specified, then calculates a percentage of the total grayscale presence in the image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetPixelColorPercentOfImage_4">GetPixelColorPercentOfImage(String, Color)</a></td><td>
Analyzes each pixel of the spcified image, counts all the pixels that are of same color as the color specified, then calculates a percentage of the total grayscale presence in the image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetPixelColorPercentOfImage_1">GetPixelColorPercentOfImage(Image, Int32, Color)</a></td><td>
Analyzes each pixel of the spcified image, counts all the pixels that are of same color as the color specified, then calculates a percentage of the total grayscale presence in the image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetPixelColorPercentOfImage_3">GetPixelColorPercentOfImage(FileInfo, Int32, Color)</a></td><td>
Analyzes each pixel of the spcified image, counts all the pixels that are of same color as the color specified, then calculates a percentage of the total grayscale presence in the image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetPixelColorPercentOfImage_5">GetPixelColorPercentOfImage(String, Int32, Color)</a></td><td>
Analyzes each pixel of the spcified image, counts all the pixels that are of same color as the color specified, then calculates a percentage of the total grayscale presence in the image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetRealWindowRect">GetRealWindowRect(IntPtr)</a></td><td>
Gets the (non-client) Rectangle of a window. 

 This method supports a borderless `Windows 10` window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetRealWindowRect_1">GetRealWindowRect(Form)</a></td><td>
Gets the (non-client) Rectangle of a window. 

 This method supports a borderless `Windows 10` window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetRealWindowRect_2">GetRealWindowRect(IWin32Window)</a></td><td>
Gets the (non-client) Rectangle of a window. 

 This method supports a borderless `Windows 10` window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_GetSystemCursorId">GetSystemCursorId</a></td><td>
Gets the (handle)identifier of the current system cursor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_OverlayImages">OverlayImages</a></td><td>
Overlay a Image over another Image used as background.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_SystemCursorIdToCursor">SystemCursorIdToCursor</a></td><td>
Retrieves an equivalent Cursor from the specified <a href="T_DevCase_Core_Imaging_SystemCursorId">SystemCursorId</a> value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_TakeScreenshotFromControl">TakeScreenshotFromControl</a></td><td>
Takes a screenshot of a Form.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_TakeScreenshotFromDesktop">TakeScreenshotFromDesktop</a></td><td>
Takes a screenshot of the desktop.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_TakeScreenshotFromForm">TakeScreenshotFromForm</a></td><td>
Takes a screenshot of a Form.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_TakeScreenshotFromObject">TakeScreenshotFromObject</a></td><td>
Takes a screenshot of an object in the screen.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_TakeScreenshotFromRegion_1">TakeScreenshotFromRegion(Rectangle, Boolean, PixelFormat)</a></td><td>
Takes a screenshot of a screen region.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_TakeScreenshotFromRegion">TakeScreenshotFromRegion(Point, Size, Boolean, PixelFormat)</a></td><td>
Takes a screenshot of a screen region.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_TakeScreenshotFromScreen">TakeScreenshotFromScreen</a></td><td>
Takes a screenshot of the specified screen.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ImageUtil_TakeScreenshotFromWpfElement">TakeScreenshotFromWpfElement</a></td><td>
Takes a screenshot of a WPF UIElement.</td></tr></table>&nbsp;
<a href="#imageutil-class">Back to Top</a>

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
<a href="#imageutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />