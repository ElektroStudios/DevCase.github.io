# NativeWindowEventNotifier Class
 

Implements basic event notification for a NativeWindow.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.NativeWindow<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticNativeWindow">DevCase.Core.Design.AestheticNativeWindow</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.NativeWindowEventNotifier<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class NativeWindowEventNotifier : AestheticNativeWindow, 
	IDisposable
```

**VB**<br />
``` VB
Public Class NativeWindowEventNotifier
	Inherits AestheticNativeWindow
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As NativeWindowEventNotifier
```

**C++**<br />
``` C++
public ref class NativeWindowEventNotifier : public AestheticNativeWindow, 
	IDisposable
```

**F#**<br />
``` F#
type NativeWindowEventNotifier =  
    class
        inherit AestheticNativeWindow
        interface IDisposable
    end
```

The NativeWindowEventNotifier type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_NativeWindowEventNotifier__ctor">NativeWindowEventNotifier</a></td><td>
Initializes a new instance of the NativeWindowEventNotifier class.</td></tr></table>&nbsp;
<a href="#nativewindoweventnotifier-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_NativeWindowEventNotifier_OwnerWindow">OwnerWindow</a></td><td>
Gets the window that owns this NativeWindowEventNotifier instance.</td></tr></table>&nbsp;
<a href="#nativewindoweventnotifier-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_NativeWindowEventNotifier_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#nativewindoweventnotifier-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_UserInterface_NativeWindowEventNotifier_Move">Move</a></td><td>
Occurs when the owner window is moving.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_UserInterface_NativeWindowEventNotifier_Resize">Resize</a></td><td>
Occurs when the owner window is resizing.</td></tr></table>&nbsp;
<a href="#nativewindoweventnotifier-class">Back to Top</a>

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
<a href="#nativewindoweventnotifier-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />