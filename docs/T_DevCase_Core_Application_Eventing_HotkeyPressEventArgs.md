# HotkeyPressEventArgs Class
 

Contains the event data for the <a href="E_DevCase_Core_Application_Hotkey_Press">Press</a> event.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.EventArgs<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticEventArgs">DevCase.Core.Design.AestheticEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.Eventing.HotkeyPressEventArgs<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Eventing">DevCase.Core.Application.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class HotkeyPressEventArgs : AestheticEventArgs
```

**VB**<br />
``` VB
Public NotInheritable Class HotkeyPressEventArgs
	Inherits AestheticEventArgs
```

**VB Usage**<br />
``` VB Usage
Dim instance As HotkeyPressEventArgs
```

**C++**<br />
``` C++
public ref class HotkeyPressEventArgs sealed : public AestheticEventArgs
```

**F#**<br />
``` F#
[<SealedAttribute>]
type HotkeyPressEventArgs =  
    class
        inherit AestheticEventArgs
    end
```

The HotkeyPressEventArgs type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Eventing_HotkeyPressEventArgs__ctor">HotkeyPressEventArgs</a></td><td>
Initializes a new instance of the HotkeyPressEventArgs class.</td></tr></table>&nbsp;
<a href="#hotkeypresseventargs-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Eventing_HotkeyPressEventArgs_Id">Id</a></td><td>
Gets the unique identifier assigned to the hotkey.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Eventing_HotkeyPressEventArgs_Key">Key</a></td><td>
Gets the key assigned to the hotkey.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Eventing_HotkeyPressEventArgs_Modifiers">Modifiers</a></td><td>
Gets the key-modifiers assigned to the hotkey.</td></tr></table>&nbsp;
<a href="#hotkeypresseventargs-class">Back to Top</a>

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
<a href="#hotkeypresseventargs-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Application_Eventing">DevCase.Core.Application.Eventing Namespace</a><br />