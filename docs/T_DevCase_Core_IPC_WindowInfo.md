# WindowInfo Class
 

Provides information of a window.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IPC.WindowInfo<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC">DevCase.Core.IPC</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class WindowInfo : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class WindowInfo
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowInfo
```

**C++**<br />
``` C++
public ref class WindowInfo sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type WindowInfo =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The WindowInfo type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IPC_WindowInfo__ctor">WindowInfo</a></td><td>
Initializes a new instance of the WindowInfo class.</td></tr></table>&nbsp;
<a href="#windowinfo-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_Active">Active</a></td><td>
Gets a value that determine whether the window is active.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_AtomWindowType">AtomWindowType</a></td><td>
Gets the window class atom.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_BorderHeight">BorderHeight</a></td><td>
Gets the height of the window border, in pixels.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_BorderWidth">BorderWidth</a></td><td>
Gets the width of the window border, in pixels.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_Bounds">Bounds</a></td><td>
Gets or sets the size and position of this window.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_ChildWindow">ChildWindow</a></td><td>
Gets the child window (if any) at the top of the Z order of this window, if this window is a parent window.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_ClassName">ClassName</a></td><td>
Gets the window class name.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_ClientRectangle">ClientRectangle</a></td><td>
Gets the size and position of the client area of this window.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_CreatorVersion">CreatorVersion</a></td><td>
Gets the Microsoft Windows version of the application that created the window.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_DeviceContext">DeviceContext</a></td><td>
Gets a handle to a device context (DC) for this window.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_Enabled">Enabled</a></td><td>
Gets a value that determine whether the window is enabled for keyboard and mouse input.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_FirstWindow">FirstWindow</a></td><td>
Gets the window (if any) of the same type of this window that is first (highest) in the Z order.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_Hwnd">Hwnd</a></td><td>
Gets the window handle.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_LastWindow">LastWindow</a></td><td>
Gets the window (if any) of the same type of this window that is last (lowest) in the Z order.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_NextWindow">NextWindow</a></td><td>
Gets the window (if any) that is next (below) this window in the Z order.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_ParentWindow">ParentWindow</a></td><td>
Gets the parent window of this window.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_PreviousWindow">PreviousWindow</a></td><td>
Gets the window (if any) that is previous (above) this window in the Z order.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_Process">Process</a></td><td>
Gets the identifier of the process that created this window.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_Screen">Screen</a></td><td>
Gets the display device on which this window is shown.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_Text">Text</a></td><td>
Gets or sets the window text.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_ThreadId">ThreadId</a></td><td>
Gets the identifier of the thread that created this window.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_Visible">Visible</a></td><td>
Gets a value that determine whether the window is visible.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_WindowExtendedStyle">WindowExtendedStyle</a></td><td>
Gets or sets the extended window styles.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_WindowPlacement">WindowPlacement</a></td><td>
Gets or sets the window placement.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_WindowInfo_WindowStyle">WindowStyle</a></td><td>
Gets or sets the window style.</td></tr></table>&nbsp;
<a href="#windowinfo-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IPC_WindowInfo_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IPC_WindowInfo_EnumerateChildWindows">EnumerateChildWindows</a></td><td>
Enumerates the child windows of this window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IPC_WindowInfo_IsChild">IsChild</a></td><td>
Determines whether this window is a child window or descendant window of a specified parent window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IPC_WindowInfo_SetForegroundWindow">SetForegroundWindow</a></td><td>
Brings the thread that created this window into the foreground, and activates the window. 

 Keyboard input is directed to the window, and various visual cues are changed for the user.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IPC_WindowInfo_ShowWindow">ShowWindow</a></td><td>
Sets the specified window's show state.</td></tr></table>&nbsp;
<a href="#windowinfo-class">Back to Top</a>

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
<a href="#windowinfo-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_IPC">DevCase.Core.IPC Namespace</a><br />