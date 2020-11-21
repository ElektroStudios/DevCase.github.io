# ProgressBarValueChangedEventArgs Class
 

Exposes the event-data of an event that notifies for value changes of a ProgressBar control.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.EventArgs<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticEventArgs">DevCase.Core.Design.AestheticEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_Eventing_ValueChangedEventArgs_1">DevCase.Controls.Eventing.ValueChangedEventArgs</a>(Int32)<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Controls.Eventing.ProgressBarValueChangedEventArgs<br />
**Namespace:**&nbsp;<a href="N_DevCase_Controls_Eventing">DevCase.Controls.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class ProgressBarValueChangedEventArgs : ValueChangedEventArgs<int>
```

**VB**<br />
``` VB
Public Class ProgressBarValueChangedEventArgs
	Inherits ValueChangedEventArgs(Of Integer)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProgressBarValueChangedEventArgs
```

**C++**<br />
``` C++
public ref class ProgressBarValueChangedEventArgs : public ValueChangedEventArgs<int>
```

**F#**<br />
``` F#
type ProgressBarValueChangedEventArgs =  
    class
        inherit ValueChangedEventArgs<int>
    end
```

The ProgressBarValueChangedEventArgs type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_Eventing_ProgressBarValueChangedEventArgs__ctor">ProgressBarValueChangedEventArgs</a></td><td>
Initializes a new instance of the ProgressBarValueChangedEventArgs class.</td></tr></table>&nbsp;
<a href="#progressbarvaluechangedeventargs-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_Eventing_ProgressBarValueChangedEventArgs_NewValue">NewValue</a></td><td>
Gets the value.
 (Overrides <a href="P_DevCase_Controls_Eventing_ValueChangedEventArgs_1_NewValue">ValueChangedEventArgs(T).NewValue</a>.)</td></tr></table>&nbsp;
<a href="#progressbarvaluechangedeventargs-class">Back to Top</a>

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
<a href="#progressbarvaluechangedeventargs-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Controls_Eventing">DevCase.Controls.Eventing Namespace</a><br />