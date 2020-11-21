# IWin32WindowExtensions Class
 

Contains custom extension methods to use with Form.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.Extensions.IWin32Window.IWin32WindowExtensions<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IWin32Window">DevCase.Core.Extensions.IWin32Window</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[HideModuleNameAttribute]
public sealed class IWin32WindowExtensions
```

**VB**<br />
``` VB
<ExtensionAttribute>
<HideModuleNameAttribute>
Public NotInheritable Class IWin32WindowExtensions
```

**VB Usage**<br />
``` VB Usage
Dim instance As IWin32WindowExtensions
```

**C++**<br />
``` C++
[ExtensionAttribute]
[HideModuleNameAttribute]
public ref class IWin32WindowExtensions sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ExtensionAttribute>]
[<HideModuleNameAttribute>]
type IWin32WindowExtensions =  class end
```

The IWin32WindowExtensions type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_PostMessage">PostMessage(IWin32Window, WindowMessages, IntPtr, IntPtr)</a></td><td>
Places (posts) a message in the message queue associated with the thread that created the specified window, and returns without waiting for the thread to process the message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_PostMessage_1">PostMessage(IWin32Window, Int32, IntPtr, IntPtr)</a></td><td>
Places (posts) a message in the message queue associated with the thread that created the specified window, and returns without waiting for the thread to process the message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_ResumeDrawing">ResumeDrawing(IWin32Window)</a></td><td>
Allow the specified window to be redrawn. 

 By calling this method, it will allow painting events to be fired on the specified window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_ResumeDrawing_1">ResumeDrawing(IWin32Window, Boolean)</a></td><td>
Allow the specified window to be redrawn. 

 By calling this method, it will allow painting events to be fired on the specified window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_SendKeyAsync">SendKeyAsync(IWin32Window, VirtualKeys, KeyBehavior)</a></td><td>
Asynchronouslly sends a keystroke to the specified window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_SendKeyAsync_1">SendKeyAsync(IWin32Window, Keys, KeyBehavior)</a></td><td>
Asynchronouslly sends a keystroke to the specified window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_SendMessage">SendMessage(IWin32Window, WindowMessages, IntPtr, IntPtr)</a></td><td>
Sends the specified message to the specified window. 

 The SendMessage function calls the window procedure for the specified window and does not return until the window procedure has processed the message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_SendMessage_1">SendMessage(IWin32Window, Int32, IntPtr, IntPtr)</a></td><td>
Sends the specified message to the specified window. 

 The SendMessage function calls the window procedure for the specified window and does not return until the window procedure has processed the message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_SendMouseButton">SendMouseButton(IWin32Window, MouseButton)</a></td><td>
Sends a mouse button click to the specified window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_SendMouseButton_1">SendMouseButton(IWin32Window, MouseButton, Point)</a></td><td>
Sends a mouse button click to the specified coordinates on the specified window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_IWin32Window_IWin32WindowExtensions_SuspendDrawing">SuspendDrawing</a></td><td>
Prevents the specified window from being redrawn. 

 By calling this method, it will disallow painting events from firing on the specified window.</td></tr></table>&nbsp;
<a href="#iwin32windowextensions-class">Back to Top</a>

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
<a href="#iwin32windowextensions-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Extensions_IWin32Window">DevCase.Core.Extensions.IWin32Window Namespace</a><br />