# DevLEDLabelMulti Class
 

A multiple LED label control. 

 The purpose of this control is to provide a representation of a LED text control.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.Control<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.ScrollableControl<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.ContainerControl<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.UserControl<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevLEDLabel">DevCase.Controls.DevLEDLabel</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Controls.DevLEDLabelMulti<br />
**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ToolboxBitmapAttribute(typeof(Label), "Label.bmp")]
[ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)]
[ComVisibleAttribute(true)]
[DefaultPropertyAttribute("Value")]
[DefaultEventAttribute("TextChanged")]
public class DevLEDLabelMulti : DevLEDLabel
```

**VB**<br />
``` VB
<ToolboxBitmapAttribute(GetType(Label), "Label.bmp")>
<ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)>
<ComVisibleAttribute(true)>
<DefaultPropertyAttribute("Value")>
<DefaultEventAttribute("TextChanged")>
Public Class DevLEDLabelMulti
	Inherits DevLEDLabel
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevLEDLabelMulti
```

**C++**<br />
``` C++
[ToolboxBitmapAttribute(typeof(Label), L"Label.bmp")]
[ClassInterfaceAttribute(ClassInterfaceType::AutoDispatch)]
[ComVisibleAttribute(true)]
[DefaultPropertyAttribute(L"Value")]
[DefaultEventAttribute(L"TextChanged")]
public ref class DevLEDLabelMulti : public DevLEDLabel
```

**F#**<br />
``` F#
[<ToolboxBitmapAttribute(typeof(Label), "Label.bmp")>]
[<ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)>]
[<ComVisibleAttribute(true)>]
[<DefaultPropertyAttribute("Value")>]
[<DefaultEventAttribute("TextChanged")>]
type DevLEDLabelMulti =  
    class
        inherit DevLEDLabel
    end
```

The DevLEDLabelMulti type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevLEDLabelMulti__ctor">DevLEDLabelMulti</a></td><td>
Initializes a new instance of the DevLEDLabelMulti class.</td></tr></table>&nbsp;
<a href="#devledlabelmulti-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevLEDLabelMulti_ColorBackground">ColorBackground</a></td><td>
Gets or sets the background color of the control.
 (Overrides <a href="P_DevCase_Controls_DevLEDLabel_ColorBackground">DevLEDLabel.ColorBackground</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevLEDLabelMulti_ColorDark">ColorDark</a></td><td>
Gets or sets the color of the LED light back.
 (Overrides <a href="P_DevCase_Controls_DevLEDLabel_ColorDark">DevLEDLabel.ColorDark</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevLEDLabelMulti_ColorLight">ColorLight</a></td><td>
Gets or sets the color of the LED light.
 (Overrides <a href="P_DevCase_Controls_DevLEDLabel_ColorLight">DevLEDLabel.ColorLight</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevLEDLabelMulti_DecimalOn">DecimalOn</a></td><td>
Gets or sets a value indicating whether the decimal point LED is turned on.
 (Overrides <a href="P_DevCase_Controls_DevLEDLabel_DecimalOn">DevLEDLabel.DecimalOn</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevLEDLabelMulti_DecimalShow">DecimalShow</a></td><td>
Gets or sets a value indicating whether the decimal point LED is displayed.
 (Overrides <a href="P_DevCase_Controls_DevLEDLabel_DecimalShow">DevLEDLabel.DecimalShow</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevLEDLabelMulti_LEDCount">LEDCount</a></td><td>
Gets or sets the amount of <a href="T_DevCase_Controls_DevLEDLabel">DevLEDLabel</a> controls that are currently displayed.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevLEDLabelMulti_Padding">Padding</a></td><td>
Gets or sets padding within the control.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevLEDLabelMulti_SegmentWidth">SegmentWidth</a></td><td>
Gets or sets the width of the LED segments.
 (Overrides <a href="P_DevCase_Controls_DevLEDLabel_SegmentWidth">DevLEDLabel.SegmentWidth</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevLEDLabelMulti_Value">Value</a></td><td>
Gets or sets the string to be displayed on the segments. 

 Supported characters are all digits and most letters.</td></tr></table>&nbsp;
<a href="#devledlabelmulti-class">Back to Top</a>

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
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_ForEachControl">ForEachControl(Boolean, Action(Control))</a></td><td>Overloaded.  
Iterate through all the controls in the source Control and performs the specified action on each one.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_ForEachControl__1">ForEachControl(T)(Boolean, Action(Control))</a></td><td>Overloaded.  
Iterate through all the controls of the specified type in the source Control and performs the specified action on each one.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_GetBoundsRelativeToForm">GetBoundsRelativeToForm</a></td><td>
Gets the bounds of the source Control relatively to its parent Form.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_GetControlStyle">GetControlStyle</a></td><td>
Gets the value of the specified ControlStyles bit for the source control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_GetEventHandlers">GetEventHandlers(String)</a></td><td>Overloaded.  
Gets all the delegates associated to the specified event raised by the source Control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Component_ComponentExtensions_GetEventHandlers">GetEventHandlers(String)</a></td><td>Overloaded.  
Gets all the delegates associated to the specified event raised by the source Component.
 (Defined by <a href="T_DevCase_Core_Extensions_Component_ComponentExtensions">ComponentExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_InvokeWhenHandleValid">InvokeWhenHandleValid</a></td><td>
Performs an action on the specified Control after its handle has been created (that is, when HandleCreated event is fired). 

 If the handle has already been created, the action is executed immediately.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_IsInDesignMode">IsInDesignMode</a></td><td>
Determines whether the source Control is in design mode.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_IsInRuntimeMode">IsInRuntimeMode</a></td><td>
Determines whether the source Control is in runtime mode.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_ResumeDrawing">ResumeDrawing()</a></td><td>Overloaded.  
Allow the source Control to be redrawn. 

 By calling this method, it will allow painting events to be fired on the source Control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_ResumeDrawing_1">ResumeDrawing(Boolean)</a></td><td>Overloaded.  
Allow the source Control to be redrawn. 

 By calling this method, it will allow painting events to be fired on the source Control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendKey_1">SendKey(Keys, KeyBehavior)</a></td><td>Overloaded.  
Sends a keystroke to the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendKey">SendKey(VirtualKeys, KeyBehavior)</a></td><td>Overloaded.  
Sends a keystroke to the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendMouseButton">SendMouseButton(MouseButton)</a></td><td>Overloaded.  
Sends a mouse button click to the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendMouseButton_1">SendMouseButton(MouseButton, Point)</a></td><td>Overloaded.  
Sends a mouse button click to the specified coordinates on the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetControlStyle">SetControlStyle</a></td><td>
Sets a specified ControlStyles flag to either `true` (`True` in Visual Basic) or `false` (`False` in Visual Basic) for the source control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetDoubleBuffer">SetDoubleBuffer</a></td><td>
Sets the value of DoubleBuffered property for the source Control. 

 You should call this method to set double buffer for a control, instead of calling <a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetControlStyle">SetControlStyle(Control, ControlStyles, Boolean)</a> method with OptimizedDoubleBuffer flag.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetVisualStyle">SetVisualStyle</a></td><td>
Changes the color appearance of the source Control using the specified style.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SuspendDrawing">SuspendDrawing</a></td><td>
Prevents the source Control from being redrawn. 

 By calling this method, it will disallow painting events from firing on the source Control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr></table>&nbsp;
<a href="#devledlabelmulti-class">Back to Top</a>

## Remarks
<a href="http://www.codeproject.com/Articles/37800/Seven-segment-LED-Control-for-NET" target="_blank">http://www.codeproject.com/Articles/37800/Seven-segment-LED-Control-for-NET</a>

## See Also


#### Reference
<a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />