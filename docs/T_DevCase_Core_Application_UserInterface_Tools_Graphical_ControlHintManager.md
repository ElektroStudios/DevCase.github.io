# ControlHintManager Class
 

Manages the control-hints of the edit-controls of a Form.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.Tools.Graphical.ControlHintManager<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ControlHintManager : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class ControlHintManager
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlHintManager
```

**C++**<br />
``` C++
public ref class ControlHintManager sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ControlHintManager =  
    class
        inherit AestheticObject
    end
```

The ControlHintManager type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlHintManager_ControlHints">ControlHints</a></td><td>
Gets the control-hints that has been created.</td></tr></table>&nbsp;
<a href="#controlhintmanager-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlHintManager_RemoveHint">RemoveHint(Control)</a></td><td>
Removes a control-hint from a control.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlHintManager_RemoveHint_1">RemoveHint(Control[])</a></td><td>
Removes a control-hint from a control.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlHintManager_SetHint">SetHint(Control, ControlHintInfo)</a></td><td>
Sets a new control-hint for an specific control.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlHintManager_SetHint_1">SetHint(Control[], ControlHintInfo)</a></td><td>
Sets a new control-hint for multiple controls at once.</td></tr></table>&nbsp;
<a href="#controlhintmanager-class">Back to Top</a>

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
<a href="#controlhintmanager-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim hintInfo1 As New ControlHintInfo("I'm a persistent hint.", Nothing,
                                     Color.Gray, ControlHintType.Normal)

Dim hintInfo2 As New ControlHintInfo("I've set this hint on multiple controls at once!", Nothing,
                                     Color.Gray, ControlHintType.Normal)

Dim hintInfo3 As New ControlHintInfo("Write something here...", New Font("lucida console", 15),
                                     Color.YellowGreen, ControlHintType.Normal)

SetHint(TextBox1, hintInfo1)
SetHint({TextBox2, TextBox3}, hintInfo2)
SetHint(RichTextBox1, hintInfo3)
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />