# WindowLocker Class
 

Selectivelly locks or unlocks various components of a window.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.NativeWindow<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticNativeWindow">DevCase.Core.Design.AestheticNativeWindow</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.WindowLocker<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class WindowLocker : AestheticNativeWindow, 
	IDisposable
```

**VB**<br />
``` VB
Public Class WindowLocker
	Inherits AestheticNativeWindow
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowLocker
```

**C++**<br />
``` C++
public ref class WindowLocker : public AestheticNativeWindow, 
	IDisposable
```

**F#**<br />
``` F#
type WindowLocker =  
    class
        inherit AestheticNativeWindow
        interface IDisposable
    end
```

The WindowLocker type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_WindowLocker__ctor">WindowLocker</a></td><td>
Initializes a new instance of the WindowLocker class.</td></tr></table>&nbsp;
<a href="#windowlocker-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_CloseButtonEnabled">CloseButtonEnabled</a></td><td>
Gets or sets a value indicating whether the Close button of the window is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_DragEnabled">DragEnabled</a></td><td>
Gets or sets a value indicating whether the window-drag of the window is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_Handle">Handle</a></td><td>
Gets the handle for the window that owns this WindowLocker instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_MaximizeButtonEnabled">MaximizeButtonEnabled</a></td><td>
Gets or sets a value indicating whether the Maximize button of the window is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_MenuEnabled">MenuEnabled</a></td><td>
Gets or sets a value indicating whether the system-menu of the window is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_MinimizeButtonEnabled">MinimizeButtonEnabled</a></td><td>
Gets or sets a value indicating whether the Minimize button of the window is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_MoveEnabled">MoveEnabled</a></td><td>
Gets or sets a value indicating whether the window-move is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_OwnerWindow">OwnerWindow</a></td><td>
Gets the window that owns this WindowLocker instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_ResizeEnabled">ResizeEnabled</a></td><td>
Gets or sets a value indicating whether the resize of the window is enabled. 

 This value takes precedence over any of the sizeable border properties.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_ScrollEnabled">ScrollEnabled</a></td><td>
Gets or sets a value indicating whether the horizontal and vertical scrolling of the window is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_SizeableBottomBorderEnabled">SizeableBottomBorderEnabled</a></td><td>
Gets or sets a value indicating whether the bottom sizable border of the window is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_SizeableBottomLeftBorderEnabled">SizeableBottomLeftBorderEnabled</a></td><td>
Gets or sets a value indicating whether the bottom-left sizable border of the window is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_SizeableBottomRightBorderEnabled">SizeableBottomRightBorderEnabled</a></td><td>
Gets or sets a value indicating whether the bottom-right sizable border of the window is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_SizeableLeftBorderEnabled">SizeableLeftBorderEnabled</a></td><td>
Gets or sets a value indicating whether the left sizable border of the window is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_SizeableRightBorderEnabled">SizeableRightBorderEnabled</a></td><td>
Gets or sets a value indicating whether the right sizable border of the window is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_SizeableTopBorderEnabled">SizeableTopBorderEnabled</a></td><td>
Gets or sets a value indicating whether the top sizable border of the window is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_SizeableTopLeftBorderEnabled">SizeableTopLeftBorderEnabled</a></td><td>
Gets or sets a value indicating whether the top-left sizable border of the window is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_WindowLocker_SizeableTopRightBorderEnabled">SizeableTopRightBorderEnabled</a></td><td>
Gets or sets a value indicating whether the top-right sizable border of the window is enabled.</td></tr></table>&nbsp;
<a href="#windowlocker-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_WindowLocker_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_WindowLocker_Lock">Lock</a></td><td>
Locks everything on the window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_WindowLocker_Unlock">Unlock</a></td><td>
Unlocks everything on the window.</td></tr></table>&nbsp;
<a href="#windowlocker-class">Back to Top</a>

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
<a href="#windowlocker-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    Friend FormLock As New WindowLocker(Me)

    Private Sub Form1_Load() Handles MyBase.Shown

        With Me.FormLock
            .CloseButtonEnabled = False
            .MaximizeButtonEnabled = False
            .MinimizeButtonEnabled = False
            .MoveEnabled = False
            .MenuEnabled = False
        End With

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />