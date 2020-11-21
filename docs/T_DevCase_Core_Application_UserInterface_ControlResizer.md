# ControlResizer Class
 

Enable or disable resize at runtime on a Control.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.ControlResizer<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ControlResizer : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class ControlResizer
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlResizer
```

**C++**<br />
``` C++
public ref class ControlResizer sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ControlResizer =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The ControlResizer type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ControlResizer__ctor">ControlResizer</a></td><td>
Initializes a new instance of the ControlResizer class.</td></tr></table>&nbsp;
<a href="#controlresizer-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ControlResizer_Control">Control</a></td><td>
Gets the owner <a href="P_DevCase_Core_Application_UserInterface_ControlResizer_Control">Control</a> used to perform resizable operations.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ControlResizer_EdgeBottomEnabled">EdgeBottomEnabled</a></td><td>
Gets or sets a value indicating whether resize is enabled on the bottom edge of the owner <a href="P_DevCase_Core_Application_UserInterface_ControlResizer_Control">Control</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ControlResizer_EdgeBottomLeftEnabled">EdgeBottomLeftEnabled</a></td><td>
Gets or sets a value indicating whether resize is enabled on the bottom-left edge of the owner <a href="P_DevCase_Core_Application_UserInterface_ControlResizer_Control">Control</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ControlResizer_EdgeBottomRightEnabled">EdgeBottomRightEnabled</a></td><td>
Gets or sets a value indicating whether resize is enabled on the bottom-right edge of the owner <a href="P_DevCase_Core_Application_UserInterface_ControlResizer_Control">Control</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ControlResizer_EdgeLeftEnabled">EdgeLeftEnabled</a></td><td>
Gets or sets a value indicating whether resize is enabled on the left edge of the owner <a href="P_DevCase_Core_Application_UserInterface_ControlResizer_Control">Control</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ControlResizer_EdgeRightEnabled">EdgeRightEnabled</a></td><td>
Gets or sets a value indicating whether resize is enabled on the right edge of the owner <a href="P_DevCase_Core_Application_UserInterface_ControlResizer_Control">Control</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ControlResizer_EdgeTopEnabled">EdgeTopEnabled</a></td><td>
Gets or sets a value indicating whether resize is enabled on the top edge of the owner <a href="P_DevCase_Core_Application_UserInterface_ControlResizer_Control">Control</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ControlResizer_EdgeTopLeftEnabled">EdgeTopLeftEnabled</a></td><td>
Gets or sets a value indicating whether resize is enabled on the top-left edge of the owner <a href="P_DevCase_Core_Application_UserInterface_ControlResizer_Control">Control</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ControlResizer_EdgeTopRightEnabled">EdgeTopRightEnabled</a></td><td>
Gets or sets a value indicating whether resize is enabled on the top-right edge of the owner <a href="P_DevCase_Core_Application_UserInterface_ControlResizer_Control">Control</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Application_UserInterface_ControlResizer_Empty">Empty</a></td><td>
Represents a ControlResizer instance that is a null reference (`Nothing` in Visual Basic).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ControlResizer_Enabled">Enabled</a></td><td>
Gets or sets a value indicating whether resize is enabled on the owner <a href="P_DevCase_Core_Application_UserInterface_ControlResizer_Control">Control</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ControlResizer_IsResizing">IsResizing</a></td><td>
Gets a value indicating whether the control is actually resizing.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ControlResizer_PixelMargin">PixelMargin</a></td><td>
Gets or sets the pixel margin required to activate resize indicators.</td></tr></table>&nbsp;
<a href="#controlresizer-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ControlResizer_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#controlresizer-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_UserInterface_ControlResizer_BeginResize">BeginResize</a></td><td>
Occurs when when the control begin to resize.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_UserInterface_ControlResizer_EndResize">EndResize</a></td><td>
Occurs when when the control ends resizing.</td></tr></table>&nbsp;
<a href="#controlresizer-class">Back to Top</a>

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
<a href="#controlresizer-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    Private ctrlResizer As ControlResizer = ControlResizer.Empty

    Private Sub Form1_Load() Handles MyBase.Load

        Me.Button1.MinimumSize = New Size(width:=24, height:=24)

        Me.ctrlResizer = New ControlResizer(Me.Button1)
        Me.ctrlResizer.Enabled = True
        Me.ctrlResizer.PixelMargin = 4

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />