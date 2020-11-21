# PauseProcessObject Class
 

Represents the return value as a result of a call to <a href="M_DevCase_Core_IPC_Tools_UIAutomationUtil_PauseProcess_1">PauseProcess(Int32)</a> and <a href="M_DevCase_Core_IPC_Tools_UIAutomationUtil_PauseThread">PauseThread(ProcessThread)</a> functions.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IPC.PauseProcessObject<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC">DevCase.Core.IPC</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class PauseProcessObject : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class PauseProcessObject
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As PauseProcessObject
```

**C++**<br />
``` C++
public ref class PauseProcessObject sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type PauseProcessObject =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The PauseProcessObject type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IPC_PauseProcessObject_PID">PID</a></td><td>
Gets the process id. (PID)</td></tr></table>&nbsp;
<a href="#pauseprocessobject-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IPC_PauseProcessObject_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#pauseprocessobject-class">Back to Top</a>

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
<a href="#pauseprocessobject-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_IPC">DevCase.Core.IPC Namespace</a><br />