# DesktopUtil Class
 

Contains Windows desktop related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.Tools.DesktopUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class DesktopUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class DesktopUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As DesktopUtil
```

**C++**<br />
``` C++
public ref class DesktopUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type DesktopUtil =  
    class
        inherit AestheticObject
    end
```

The DesktopUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_DesktopUtil_ClassName">ClassName</a></td><td>
Gets the class name of the Desktop window (the window that contains the icons).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Shell_Tools_DesktopUtil_Folder">Folder</a></td><td>
Gets a Folder2 instance that represents the Desktop virtual folder.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_DesktopUtil_Hwnd">Hwnd</a></td><td>
Gets the window handle of the Desktop window (the window that contains the icons).</td></tr></table>&nbsp;
<a href="#desktoputil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_DesktopUtil_CascadeWindows">CascadeWindows</a></td><td>
Cascades all of the windows on the desktop. This method has the same effect as right-clicking the taskbar and selecting Cascade Windows.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_DesktopUtil_Hide">Hide</a></td><td>
Hides the desktop.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_DesktopUtil_Lock">Lock</a></td><td>
Locks the WorkStation.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_DesktopUtil_RunScreensaver">RunScreensaver</a></td><td>
Runs the default screensaver. 

 ( the screensaver should be enabled. )</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_DesktopUtil_SetIconViewMode">SetIconViewMode</a></td><td>
Sets the view mode of the desktop icons.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_DesktopUtil_Show">Show</a></td><td>
Shows/Restores the desktop.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_DesktopUtil_TileWindowsHorizontally">TileWindowsHorizontally</a></td><td>
Tiles all of the windows on the desktop horizontally. This method has the same effect as right-clicking the taskbar and selecting Tile Windows Horizontally.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_DesktopUtil_TileWindowsVertically">TileWindowsVertically</a></td><td>
Tiles all of the windows on the desktop vertically. 

 This method has the same effect as right-clicking the taskbar and selecting Tile Windows Vertically.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_DesktopUtil_ToggleState">ToggleState</a></td><td>
Toggles the visibility state of the desktop.</td></tr></table>&nbsp;
<a href="#desktoputil-class">Back to Top</a>

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
<a href="#desktoputil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />