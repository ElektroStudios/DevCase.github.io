# WindowToScreenDocker Class
 

Docks a window around the edges of the screen.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.NativeWindow<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticNativeWindow">DevCase.Core.Design.AestheticNativeWindow</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.WindowToScreenDocker<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class WindowToScreenDocker : AestheticNativeWindow, 
	IDisposable
```

**VB**<br />
``` VB
Public Class WindowToScreenDocker
	Inherits AestheticNativeWindow
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowToScreenDocker
```

**C++**<br />
``` C++
public ref class WindowToScreenDocker : public AestheticNativeWindow, 
	IDisposable
```

**F#**<br />
``` F#
type WindowToScreenDocker =  
    class
        inherit AestheticNativeWindow
        interface IDisposable
    end
```

The WindowToScreenDocker type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_WindowToScreenDocker__ctor">WindowToScreenDocker(IWin32Window)</a></td><td>
Initializes a new instance of the WindowToScreenDocker class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_WindowToScreenDocker__ctor_1">WindowToScreenDocker(IWin32Window, Screen)</a></td><td>
Initializes a new instance of the WindowToScreenDocker class.</td></tr></table>&nbsp;
<a href="#windowtoscreendocker-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowToScreenDocker_EnableMove">EnableMove</a></td><td>
Gets or sets a value that indicates whether the window-moving is enabled. 

 If `false` (`False` in Visual Basic), the window cannot be moved.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowToScreenDocker_EnableResize">EnableResize</a></td><td>
Gets or sets a value that indicates whether the window-resizing is enabled. 

 If `false` (`False` in Visual Basic), the window cannot be resized.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowToScreenDocker_Handle">Handle</a></td><td>
Gets the handle for the window that owns this WindowToScreenDocker instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowToScreenDocker_IsDocked">IsDocked</a></td><td>
Gets a value indicating whether the window is docked.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowToScreenDocker_OwnerWindow">OwnerWindow</a></td><td>
Gets the window that owns this WindowToScreenDocker instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowToScreenDocker_Position">Position</a></td><td>
Gets the current <a href="T_DevCase_Core_Application_UserInterface_ScreenDockingPosition">ScreenDockingPosition</a> of the window.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowToScreenDocker_Screen">Screen</a></td><td>
Gets or sets the target <a href="P_DevCase_Core_Application_UserInterface_WindowToScreenDocker_Screen">Screen</a> where the docking will be performed.</td></tr></table>&nbsp;
<a href="#windowtoscreendocker-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_WindowToScreenDocker_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_WindowToScreenDocker_Dock">Dock</a></td><td>
Docks the window to a specified position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_WindowToScreenDocker_Undock">Undock</a></td><td>
Disables the window docking.</td></tr></table>&nbsp;
<a href="#windowtoscreendocker-class">Back to Top</a>

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
<a href="#windowtoscreendocker-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Friend WindowDock As New WindowToScreenDocker(Me) With
    {
        .EnableMove = False,
        .EnableResize = True
    }

Private Sub Test()

    Me.WindowDock.Dock(ScreenDockingPosition.WorkingAreaBottomRight)

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />