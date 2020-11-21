# AestheticComponent Class
 

This is a class to consume for aesthetic purposes. 

 A default (emptyness) class that inherits from Component, with these base members hidden: 

Container, SiteGetHashCode(), GetType(), Equals(Object), Equals(Object, Object), ReferenceEquals(Object, Object), ToString().


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Design.AestheticComponent<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#inheritance-hierarchy">More...</a>
**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)]
[ComVisibleAttribute(true)]
public abstract class AestheticComponent : Component
```

**VB**<br />
``` VB
<ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)>
<ComVisibleAttribute(true)>
Public MustInherit Class AestheticComponent
	Inherits Component
```

**VB Usage**<br />
``` VB Usage
Dim instance As AestheticComponent
```

**C++**<br />
``` C++
[ClassInterfaceAttribute(ClassInterfaceType::AutoDispatch)]
[ComVisibleAttribute(true)]
public ref class AestheticComponent abstract : public Component
```

**F#**<br />
``` F#
[<AbstractClassAttribute>]
[<ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)>]
[<ComVisibleAttribute(true)>]
type AestheticComponent =  
    class
        inherit Component
    end
```

The AestheticComponent type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_AestheticComponent__ctor">AestheticComponent</a></td><td>
Initializes a new instance of the AestheticComponent class.</td></tr></table>&nbsp;
<a href="#aestheticcomponent-class">Back to Top</a>

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
<a href="#aestheticcomponent-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />

## Inheritance HierarchySystem.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Design.AestheticComponent<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevCheckBoxData_DevCheckBoxBorderLayout">DevCase.Controls.DevCheckBoxData.DevCheckBoxBorderLayout</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevCheckBoxData_DevCheckBoxStateLayout">DevCase.Controls.DevCheckBoxData.DevCheckBoxStateLayout</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevComboBoxData_DevComboBoxBorderLayout">DevCase.Controls.DevComboBoxData.DevComboBoxBorderLayout</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevComboBoxData_DevComboBoxStateLayout">DevCase.Controls.DevComboBoxData.DevComboBoxStateLayout</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevListBoxData_DevListBoxGridLayout">DevCase.Controls.DevListBoxData.DevListBoxGridLayout</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevListBoxData_DevListBoxItemLayout">DevCase.Controls.DevListBoxData.DevListBoxItemLayout</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevListBoxData_DevListBoxItemLayoutColors">DevCase.Controls.DevListBoxData.DevListBoxItemLayoutColors</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevListBoxData_DevListBoxStateLayout">DevCase.Controls.DevListBoxData.DevListBoxStateLayout</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevListBoxData_DevListBoxStringFormatLayout">DevCase.Controls.DevListBoxData.DevListBoxStringFormatLayout</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevNumericUpDownData_DevNumericUpDownBorderLayout">DevCase.Controls.DevNumericUpDownData.DevNumericUpDownBorderLayout</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevNumericUpDownData_DevNumericUpDownStateLayout">DevCase.Controls.DevNumericUpDownData.DevNumericUpDownStateLayout</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevRichTextBoxData_DevRichTextBoxBorderLayout">DevCase.Controls.DevRichTextBoxData.DevRichTextBoxBorderLayout</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevRichTextBoxData_DevRichTextBoxStateLayout">DevCase.Controls.DevRichTextBoxData.DevRichTextBoxStateLayout</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevTextBoxData_DevTextBoxBorderLayout">DevCase.Controls.DevTextBoxData.DevTextBoxBorderLayout</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_DevTextBoxData_DevTextBoxStateLayout">DevCase.Controls.DevTextBoxData.DevTextBoxStateLayout</a><br />