# MouseHook Class
 

**Note: This API is now obsolete.**

A low level mouse hook that processes mouse input events.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.IO.MouseHook<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("This class is obsolete. Use 'DevCase.Core.IO.MouseMonitor' instead.", 
	false)]
public sealed class MouseHook : IDisposable
```

**VB**<br />
``` VB
<ObsoleteAttribute("This class is obsolete. Use 'DevCase.Core.IO.MouseMonitor' instead.", 
	false)>
Public NotInheritable Class MouseHook
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseHook
```

**C++**<br />
``` C++
[ObsoleteAttribute(L"This class is obsolete. Use 'DevCase.Core.IO.MouseMonitor' instead.", 
	false)]
public ref class MouseHook sealed : IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ObsoleteAttribute("This class is obsolete. Use 'DevCase.Core.IO.MouseMonitor' instead.", 
	false)>]
type MouseHook =  
    class
        interface IDisposable
    end
```

The MouseHook type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_MouseHook__ctor">MouseHook</a></td><td>
Initializes a new instance of the mouseHook class.</td></tr></table>&nbsp;
<a href="#mousehook-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseHook_IsEnabled">IsEnabled</a></td><td>
Gets a value indicating whether the Hook is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseHook_IsInstalled">IsInstalled</a></td><td>
Gets a value indicating whether the Hook is installed.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseHook_SuppressMouseButtonUpEventWhenDoubleClick">SuppressMouseButtonUpEventWhenDoubleClick</a></td><td>
** ONLY FOR TESTING PURPOSES ** 

 Gets or sets a value indicating whether to suppress the last `MouseUp` event of when a double-click occurs. 

 If this value is set to `true` (`True` in Visual Basic), the application will send the events in this order for a Double-Click: 

`MouseDown`, `MouseUp`, `MouseDown`, `MouseDoubleClick`

 If this value is set to `false` (`False` in Visual Basic), the application will send the events in this order for a Double-Click: `MouseDown`, `MouseUp`, `MouseDown`, `MouseUp`, `MouseDoubleClick`</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseHook_WorkingArea">WorkingArea</a></td><td>
Gets or sets the screen's working area on which to notify about mouse events. 

 The events fired by this mouseHook will be restricted to the bounds of the specified rectangle.</td></tr></table>&nbsp;
<a href="#mousehook-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_MouseHook_Disable">Disable</a></td><td>
Temporally disables the Mouse Hook events. 

 To re-enable the events, call the <a href="M_DevCase_Core_IO_MouseHook_Enable">Enable()</a> method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_MouseHook_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_MouseHook_Enable">Enable</a></td><td>
Enables the Mouse Hook events.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_MouseHook_Install">Install</a></td><td>
Installs the Mouse Hook, then start processing messages to fire events.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_MouseHook_Uninstall">Uninstall</a></td><td>
Uninstalls the Mouse Hook and free all resources, then stop processing messages to fire events.</td></tr></table>&nbsp;
<a href="#mousehook-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_MouseHook_MouseButtonClick">MouseButtonClick</a></td><td>
Occurs when a mouse button is pressed or released.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_MouseHook_MouseButtonDoubleClick">MouseButtonDoubleClick</a></td><td>
Occurs when the mouse performs a double-click on a button. 

 A double click is considered as: (MouseButtonDown + MouseButtonUp) * 2</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_MouseHook_MouseMove">MouseMove</a></td><td>
Occurs when the mouse moves.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_MouseHook_MouseWheel">MouseWheel</a></td><td>
Occurs when the mouse wheel is moved up or down.</td></tr></table>&nbsp;
<a href="#mousehook-class">Back to Top</a>

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
<a href="#mousehook-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />