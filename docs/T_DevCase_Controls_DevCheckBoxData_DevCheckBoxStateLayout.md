# DevCheckBoxStateLayout Class
 

Provides the layout that determines the appearance of a <a href="T_DevCase_Controls_DevCheckBox">DevCheckBox</a> control.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticComponent">DevCase.Core.Design.AestheticComponent</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Controls.DevCheckBoxData.DevCheckBoxStateLayout<br />
**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevCheckBoxData">DevCase.Controls.DevCheckBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class DevCheckBoxStateLayout : AestheticComponent
```

**VB**<br />
``` VB
Public NotInheritable Class DevCheckBoxStateLayout
	Inherits AestheticComponent
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevCheckBoxStateLayout
```

**C++**<br />
``` C++
public ref class DevCheckBoxStateLayout sealed : public AestheticComponent
```

**F#**<br />
``` F#
[<SealedAttribute>]
type DevCheckBoxStateLayout =  
    class
        inherit AestheticComponent
    end
```

The DevCheckBoxStateLayout type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevCheckBoxData_DevCheckBoxStateLayout__ctor">DevCheckBoxStateLayout</a></td><td>
Initializes a new instance of the DevCheckBoxStateLayout class.</td></tr></table>&nbsp;
<a href="#devcheckboxstatelayout-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevCheckBoxData_DevCheckBoxStateLayout_BackColor">BackColor</a></td><td>
Gets or sets the background color of the control.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevCheckBoxData_DevCheckBoxStateLayout_Border">Border</a></td><td>
Gets the border layout of the control.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevCheckBoxData_DevCheckBoxStateLayout_BoxBackgroundImage">BoxBackgroundImage</a></td><td>
Gets or sets the image of the checkbox box.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevCheckBoxData_DevCheckBoxStateLayout_BoxColor">BoxColor</a></td><td>
Gets or sets the color of the checkbox box.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevCheckBoxData_DevCheckBoxStateLayout_Cursor">Cursor</a></td><td>
Gets the cursor that appears when the pointer moves over the control.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevCheckBoxData_DevCheckBoxStateLayout_Font">Font</a></td><td>
Gets or sets the font of the text displayed by the control.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevCheckBoxData_DevCheckBoxStateLayout_ForeColor">ForeColor</a></td><td>
Gets or sets the foreground color of the control.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevCheckBoxData_DevCheckBoxStateLayout_TickColor">TickColor</a></td><td>
Gets or sets the color of the checkbox tick.</td></tr></table>&nbsp;
<a href="#devcheckboxstatelayout-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevCheckBoxData_DevCheckBoxStateLayout_ResetFont">ResetFont</a></td><td>
Sets the <a href="P_DevCase_Controls_DevCheckBoxData_DevCheckBoxStateLayout_Font">Font</a> property to its default value.</td></tr></table>&nbsp;
<a href="#devcheckboxstatelayout-class">Back to Top</a>

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
<a href="#devcheckboxstatelayout-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Controls_DevCheckBoxData">DevCase.Controls.DevCheckBoxData Namespace</a><br />