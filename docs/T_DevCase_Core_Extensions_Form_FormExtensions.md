# FormExtensions Class
 

Contains custom extension methods to use with Form.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.Extensions.Form.FormExtensions<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[HideModuleNameAttribute]
public sealed class FormExtensions
```

**VB**<br />
``` VB
<ExtensionAttribute>
<HideModuleNameAttribute>
Public NotInheritable Class FormExtensions
```

**VB Usage**<br />
``` VB Usage
Dim instance As FormExtensions
```

**C++**<br />
``` C++
[ExtensionAttribute]
[HideModuleNameAttribute]
public ref class FormExtensions sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ExtensionAttribute>]
[<HideModuleNameAttribute>]
type FormExtensions =  class end
```

The FormExtensions type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Form_FormExtensions_ForEachControl">ForEachControl(Form, Boolean, Action(Control))</a></td><td>
Iterate through all the controls in the source Form and performs the specified action on each one.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Form_FormExtensions_ForEachControl__1">ForEachControl(T)(Form, Boolean, Action(Control))</a></td><td>
Iterate through all the controls of the specified type in the source Form and performs the specified action on each one.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Form_FormExtensions_GetEventHandlers">GetEventHandlers</a></td><td>
Gets all the delegates associated to the specified event raised by the source Form.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Form_FormExtensions_GetHorizontalBorderSize">GetHorizontalBorderSize</a></td><td>
Gets the size of the horizontal border (the border of the top or bottom edge) of the source Form.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Form_FormExtensions_GetTitleBarBounds">GetTitleBarBounds</a></td><td>
Gets the titlebar bounds of the source Form.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Form_FormExtensions_GetVerticalBorderSize">GetVerticalBorderSize</a></td><td>
Gets the size of the vertical border (the border of the left or right edge) of the source Form.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Form_FormExtensions_LockFormRegionToControls">LockFormRegionToControls(Form)</a></td><td>
Locks the window region of the specified Form to the bounds of its child controls.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Form_FormExtensions_LockFormRegionToControls__1">LockFormRegionToControls(T)(Form)</a></td><td>
Locks the window region of the specified Form to the bounds of its child controls of the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Form_FormExtensions_ResumeDrawing">ResumeDrawing(Form)</a></td><td>
Allow the source Form to be redrawn. 

 By calling this method, it will allow painting events to be fired on the source Form.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Form_FormExtensions_ResumeDrawing_1">ResumeDrawing(Form, Boolean)</a></td><td>
Allow the source Form to be redrawn. 

 By calling this method, it will allow painting events to be fired on the source Form.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Form_FormExtensions_SetVisualStyle">SetVisualStyle</a></td><td>
Changes the color appearance of the source <a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form</a> using the specified style.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Form_FormExtensions_SuspendDrawing">SuspendDrawing</a></td><td>
Prevents the source Form from being redrawn. 

 By calling this method, it will disallow painting events from firing on the source Form.</td></tr></table>&nbsp;
<a href="#formextensions-class">Back to Top</a>

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
<a href="#formextensions-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form Namespace</a><br />