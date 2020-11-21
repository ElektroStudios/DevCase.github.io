# MouseMonitor Class
 

Handles the raw input from mouse devices.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.NativeWindow<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticNativeWindow">DevCase.Core.Design.AestheticNativeWindow</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.MouseMonitor<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class MouseMonitor : AestheticNativeWindow, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class MouseMonitor
	Inherits AestheticNativeWindow
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseMonitor
```

**C++**<br />
``` C++
public ref class MouseMonitor sealed : public AestheticNativeWindow, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type MouseMonitor =  
    class
        inherit AestheticNativeWindow
        interface IDisposable
    end
```

The MouseMonitor type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_MouseMonitor__ctor">MouseMonitor</a></td><td>
Initializes a new instance of the MouseMonitor class. 

 Caling this constructor causes to registers the raw input devices for the calling window.</td></tr></table>&nbsp;
<a href="#mousemonitor-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseMonitor_DeviceCount">DeviceCount</a></td><td>
Gets the amount of mouse devices.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseMonitor_Enabled">Enabled</a></td><td>
Gets or sets a value that determines whether the mouselogger is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseMonitor_Handle">Handle</a></td><td>
Gets the handle for the window that owns this MouseMonitor instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseMonitor_OwnerWindow">OwnerWindow</a></td><td>
Gets the window that owns this MouseMonitor instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseMonitor_SuppressMouseButtonUpEventWhenDoubleClick">SuppressMouseButtonUpEventWhenDoubleClick</a></td><td>
** ONLY FOR TESTING PURPOSES ** 

 Gets or sets a value indicating whether to suppress the last `MouseUp` event of when a double-click occurs. 

 If this value is set to `true` (`True` in Visual Basic), the application will send the events in this order for a Double-Click: 

`MouseDown`, `MouseUp`, `MouseDown`, `MouseDoubleClick`

 If this value is set to `false` (`False` in Visual Basic), the application will send the events in this order for a Double-Click: `MouseDown`, `MouseUp`, `MouseDown`, `MouseUp`, `MouseDoubleClick`</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_MouseMonitor_WorkingArea">WorkingArea</a></td><td>
Gets or sets the screen's working area on which to notify about mouse events. 

 The events fired by this MouseMonitor will be restricted to the bounds of the specified rectangle.</td></tr></table>&nbsp;
<a href="#mousemonitor-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_MouseMonitor_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#mousemonitor-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_MouseMonitor_MouseButtonClick">MouseButtonClick</a></td><td>
Occurs when a mouse button is clicked.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_MouseMonitor_MouseButtonDoubleClick">MouseButtonDoubleClick</a></td><td>
Occurs when a mouse button is clicked twice producing a double-click.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_MouseMonitor_MouseMove">MouseMove</a></td><td>
Occurs when the mouse moves.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_MouseMonitor_MouseWheelScroll">MouseWheelScroll</a></td><td>
Occurs when the mouse wheel scrolls up or down.</td></tr></table>&nbsp;
<a href="#mousemonitor-class">Back to Top</a>

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
<a href="#mousemonitor-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public NotInheritable Class Form1 : Inherits Form

    Friend WithEvents MouseMon As New MouseMonitor(Me)

    Private Sub Form1_Shown(ByVal sender As Object, ByVal e As EventArgs) _
    Handles MyBase.Shown

        Me.MouseMon.WorkingArea = SystemInformation.VirtualScreen
        Me.MouseMon.SuppressMouseButtonUpEventWhenDoubleClick = False
        Me.MouseMon.Enabled = True

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Handles the <see cref="MouseMonitor.MouseMove"/> event of the <see cref="MouseMon"/> instance.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="sender">
    ''' The source of the event.
    ''' </param>
    '''
    ''' <param name="e">
    ''' The <see cref="MouseMoveEventArgs"/> instance containing the event data.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Private Sub MouseMon_MouseMove(ByVal sender As Object, ByVal e As MouseMoveEventArgs) _
    Handles MouseMon.MouseMove

        Console.WriteLine(String.Format("Mouse moved to: {0}", e.Position.ToString()))

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Handles the <see cref="MouseMonitor.MouseButtonClick"/> event of the <see cref="MouseMon"/> instance.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="sender">
    ''' The source of the event.
    ''' </param>
    '''
    ''' <param name="e">
    ''' The <see cref="MouseButtonClickEventArgs"/> instance containing the event data.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Private Sub MouseMon_MouseButtonClick(ByVal sender As Object, ByVal e As MouseButtonClickEventArgs) _
    Handles MouseMon.MouseButtonClick

        Console.WriteLine(String.Format("Mouse Button Click: {0,-10} at: {1}", e.MouseButton.ToString(), e.DeviceInfo.Position.ToString()))

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Handles the <see cref="MouseMonitor.MouseButtonDoubleClick"/> event of the <see cref="MouseMon"/> instance.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="sender">
    ''' The source of the event.
    ''' </param>
    '''
    ''' <param name="e">
    ''' The <see cref="MouseButtonDoubleClickEventArgs"/> instance containing the event data.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Private Sub MouseMon_MouseButtonDoubleClick(ByVal sender As Object, ByVal e As MouseButtonDoubleClickEventArgs) _
    Handles MouseMon.MouseButtonDoubleClick

        Console.WriteLine(String.Format("Mouse Button Double-Click: {0,-5} at: {1}", e.MouseButton.ToString(), e.DeviceInfo.Position.ToString()))

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Handles the <see cref="MouseMonitor.MouseWheelScroll"/> event of the <see cref="MouseMon"/> instance.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="sender">
    ''' The source of the event.
    ''' </param>
    '''
    ''' <param name="e">
    ''' The <see cref="MouseWheelScrollEventArgs"/> instance containing the event data.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Private Sub MouseMon_MouseWheelScroll(ByVal sender As Object, ByVal e As MouseWheelScrollEventArgs) _
    Handles MouseMon.MouseWheelScroll

        Console.WriteLine(String.Format("Mouse wheel scrolled to: {0}", e.WheelDirection.ToString()))

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />