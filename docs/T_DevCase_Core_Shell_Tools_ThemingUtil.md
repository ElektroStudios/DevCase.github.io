# ThemingUtil Class
 

Contains cursor related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.Tools.ThemingUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ThemingUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class ThemingUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As ThemingUtil
```

**C++**<br />
``` C++
public ref class ThemingUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ThemingUtil =  
    class
        inherit AestheticObject
    end
```

The ThemingUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_ThemingUtil_AeroEnabled">AeroEnabled</a></td><td>
Gets a value indicating whether Aero feature is enabled on the current operating system.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_ThemingUtil_AeroSupported">AeroSupported</a></td><td>
Gets a value indicating whether Aero feature is supported by the current operating system.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_ThemingUtil_CurrentScreensaver">CurrentScreensaver</a></td><td>
Gets the path of the current screensaver.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_ThemingUtil_CurrentTheme">CurrentTheme</a></td><td>
Gets a <a href="T_DevCase_Core_Shell_ThemeInfo">ThemeInfo</a> object that contains the info of the current windows theme.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_ThemingUtil_CurrentWallpaper">CurrentWallpaper</a></td><td>
Gets the filepath of the current desktop wallpaper.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_Tools_ThemingUtil_InstalledFontNames">InstalledFontNames</a></td><td>
Gets the names of the font families installed on the current machine.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_Tools_ThemingUtil_InstalledFonts">InstalledFonts</a></td><td>
Gets the font families installed on the current machine.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_ThemingUtil_WallpaperAsJpegIsSupported">WallpaperAsJpegIsSupported</a></td><td>
Gets a value that determines wheter jpeg files are supported as wallpaper in the current operating system. The jpeg wallpapers are not supported before Windows Vista.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_ThemingUtil_WallpaperStylesFitFillAreSupported">WallpaperStylesFitFillAreSupported</a></td><td>
Gets a value that determines whether the <a href="T_DevCase_Core_Shell_WallpaperStyle">Fit</a> and <a href="T_DevCase_Core_Shell_WallpaperStyle">Fill</a> are supported in the current operating system. The <a href="T_DevCase_Core_Shell_WallpaperStyle">Fit</a> and <a href="T_DevCase_Core_Shell_WallpaperStyle">Fill</a> wallpaper styles are not supported before Windows 7.</td></tr></table>&nbsp;
<a href="#themingutil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_ThemingUtil_IsFontInstalled">IsFontInstalled(FontFamily)</a></td><td>
Determines whether a text-font is installed on the current machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_ThemingUtil_IsFontInstalled_1">IsFontInstalled(String)</a></td><td>
Determines whether a text-font is installed on the current machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_ThemingUtil_RemoveDesktopWallpaper">RemoveDesktopWallpaper</a></td><td>
Removes the current desktop wallpaper from screen.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_ThemingUtil_SetDesktopWallpaper">SetDesktopWallpaper</a></td><td>
Sets the current desktop wallpaper.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_ThemingUtil_SetScreensaver">SetScreensaver</a></td><td>
Sets the system screensaver.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Shell_Tools_ThemingUtil_SetSystemCursor">SetSystemCursor</a></td><td>
Sets the system cursor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Shell_Tools_ThemingUtil_SetSystemVisualTheme">SetSystemVisualTheme</a></td><td>
Sets the system visual theme.</td></tr></table>&nbsp;
<a href="#themingutil-class">Back to Top</a>

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
<a href="#themingutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />