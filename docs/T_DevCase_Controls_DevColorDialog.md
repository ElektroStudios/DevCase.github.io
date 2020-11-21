# DevColorDialog Class
 

A extended ColorDialog dialog box.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.CommonDialog<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.ColorDialog<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Controls.DevColorDialog<br />
**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ToolboxBitmapAttribute(typeof(ColorDialog), "ColorDialog.bmp")]
[DefaultPropertyAttribute("Color")]
[DefaultEventAttribute("SelectedColorChanged")]
public class DevColorDialog : ColorDialog
```

**VB**<br />
``` VB
<ToolboxBitmapAttribute(GetType(ColorDialog), "ColorDialog.bmp")>
<DefaultPropertyAttribute("Color")>
<DefaultEventAttribute("SelectedColorChanged")>
Public Class DevColorDialog
	Inherits ColorDialog
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevColorDialog
```

**C++**<br />
``` C++
[ToolboxBitmapAttribute(typeof(ColorDialog), L"ColorDialog.bmp")]
[DefaultPropertyAttribute(L"Color")]
[DefaultEventAttribute(L"SelectedColorChanged")]
public ref class DevColorDialog : public ColorDialog
```

**F#**<br />
``` F#
[<ToolboxBitmapAttribute(typeof(ColorDialog), "ColorDialog.bmp")>]
[<DefaultPropertyAttribute("Color")>]
[<DefaultEventAttribute("SelectedColorChanged")>]
type DevColorDialog =  
    class
        inherit ColorDialog
    end
```

The DevColorDialog type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevColorDialog__ctor">DevColorDialog</a></td><td>
Initializes a new instance of the DevColorDialog class.</td></tr></table>&nbsp;
<a href="#devcolordialog-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevColorDialog_FullOpen">FullOpen</a></td><td>
Gets or sets a value indicating whether the custom color section of the dialog box is initially displayed.
 (Overrides ColorDialog.FullOpen.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevColorDialog_Location">Location</a></td><td>
Gets or sets the location, in screen coordinates, of the dialog window.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevColorDialog_StartPosition">StartPosition</a></td><td>
Gets or sets the position of the dialog window when it first appears.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevColorDialog_Text">Text</a></td><td>
Gets or sets the text that will be shown on the titlebar of the dialog window.</td></tr></table>&nbsp;
<a href="#devcolordialog-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Controls_DevColorDialog_SelectedColorChanged">SelectedColorChanged</a></td><td>
Occurs when the current selected color has changed.</td></tr></table>&nbsp;
<a href="#devcolordialog-class">Back to Top</a>

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
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Component_ComponentExtensions_GetEventHandlers">GetEventHandlers</a></td><td>
Gets all the delegates associated to the specified event raised by the source Component.
 (Defined by <a href="T_DevCase_Core_Extensions_Component_ComponentExtensions">ComponentExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#devcolordialog-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />