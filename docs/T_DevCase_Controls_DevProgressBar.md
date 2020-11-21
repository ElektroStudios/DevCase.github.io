# DevProgressBar Class
 

A extended ProgressBar control.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.Control<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.ProgressBar<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Controls.DevProgressBar<br />
**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ToolboxBitmapAttribute(typeof(ProgressBar), "ProgressBar.bmp")]
[ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)]
[ComVisibleAttribute(true)]
[DefaultBindingPropertyAttribute("Value")]
[DefaultPropertyAttribute("Value")]
[DefaultEventAttribute("ValueChanged")]
public class DevProgressBar : ProgressBar, 
	IBufferedControl
```

**VB**<br />
``` VB
<ToolboxBitmapAttribute(GetType(ProgressBar), "ProgressBar.bmp")>
<ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)>
<ComVisibleAttribute(true)>
<DefaultBindingPropertyAttribute("Value")>
<DefaultPropertyAttribute("Value")>
<DefaultEventAttribute("ValueChanged")>
Public Class DevProgressBar
	Inherits ProgressBar
	Implements IBufferedControl
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevProgressBar
```

**C++**<br />
``` C++
[ToolboxBitmapAttribute(typeof(ProgressBar), L"ProgressBar.bmp")]
[ClassInterfaceAttribute(ClassInterfaceType::AutoDispatch)]
[ComVisibleAttribute(true)]
[DefaultBindingPropertyAttribute(L"Value")]
[DefaultPropertyAttribute(L"Value")]
[DefaultEventAttribute(L"ValueChanged")]
public ref class DevProgressBar : public ProgressBar, 
	IBufferedControl
```

**F#**<br />
``` F#
[<ToolboxBitmapAttribute(typeof(ProgressBar), "ProgressBar.bmp")>]
[<ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)>]
[<ComVisibleAttribute(true)>]
[<DefaultBindingPropertyAttribute("Value")>]
[<DefaultPropertyAttribute("Value")>]
[<DefaultEventAttribute("ValueChanged")>]
type DevProgressBar =  
    class
        inherit ProgressBar
        interface IBufferedControl
    end
```

The DevProgressBar type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevProgressBar__ctor">DevProgressBar</a></td><td>
Initializes a new instance of the DevProgressBar class.</td></tr></table>&nbsp;
<a href="#devprogressbar-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressBar_BorderColor">BorderColor</a></td><td>
Gets or sets the border color of the control.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressBar_DoubleBuffered">DoubleBuffered</a></td><td>
Gets or sets a value indicating whether this control should redraw its surface using a secondary buffer to reduce or prevent flicker.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressBar_Font">Font</a></td><td>
Gets or sets the Font of the text displayed by the control.
 (Overrides ProgressBar.Font().)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressBar_ForeColor">ForeColor</a></td><td>
Gets or sets the color of the text displayed by the control.
 (Overrides Control.ForeColor.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressBar_FormatString">FormatString</a></td><td>
Gets or sets the percentage format string that will be displayed on the control when its current state is <a href="T_DevCase_Controls_DevProgressBarData_DevProgressBarState">Normal</a>. 

 #current=Current Value #total=Maximum Value #%=Current Percentage</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressBar_FormatStringError">FormatStringError</a></td><td>
Gets or sets the percentage format string that will be displayed on the control when its current state is <a href="T_DevCase_Controls_DevProgressBarData_DevProgressBarState">Error</a>. 

 #current=Current Value #total=Maximum Value #%=Current Percentage</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressBar_FormatStringPaused">FormatStringPaused</a></td><td>
Gets or sets the percentage format string that will be displayed on the control when its current state is <a href="T_DevCase_Controls_DevProgressBarData_DevProgressBarState">Paused</a>. 

 #current=Current Value #total=Maximum Value #%=Current Percentage</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressBar_PreventFlickering">PreventFlickering</a></td><td>
Gets or sets a value that indicates whether the control should avoid unwanted flickering effects. 

 If `true` (`True` in Visual Basic), this will avoid any flickering effect on the control, however, it will also have a negative impact by slowing down the responsiveness of the control about to 30% slower. 

 This negative impact doesn't affect to the performance of the application itself, just to the performance of this control.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressBar_ShowBorder">ShowBorder</a></td><td>
Gets or sets a value indicating whether the border of the control is shown.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressBar_State">State</a></td><td>
Gets or sets the state (and fill color) of the progress bar.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevProgressBar_Value">Value</a></td><td>
Gets or sets the current value of the progress bar.</td></tr></table>&nbsp;
<a href="#devprogressbar-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevProgressBar_Increment">Increment</a></td><td>
Advances the current position of the progress bar by the specified amount.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevProgressBar_PerformStep">PerformStep</a></td><td>
Advances the current position of the progress bar by the amount of the Step property.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevProgressBar_ResetFont">ResetFont</a></td><td>
Sets the <a href="P_DevCase_Controls_DevProgressBar_Font">Font</a> property to its default value.
 (Overrides Control.ResetFont().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevProgressBar_ToString">ToString</a></td><td>
Returns a string representation for this DevProgressBar.
 (Overrides ProgressBar.ToString().)</td></tr></table>&nbsp;
<a href="#devprogressbar-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")![Code example](media/CodeExample.png "Code example")</td><td><a href="E_DevCase_Controls_DevProgressBar_ValueChanged">ValueChanged</a></td><td>
Occurs when the progress bar value changes.</td></tr></table>&nbsp;
<a href="#devprogressbar-class">Back to Top</a>

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
<a href="#devprogressbar-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />