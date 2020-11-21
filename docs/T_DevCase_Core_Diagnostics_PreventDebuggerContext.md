# PreventDebuggerContext Class
 

Prevents a debugger in user-mode from being attached to the current process, and immediately terminates the current process after writing a message to the Windows Application event log.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Diagnostics.PreventDebuggerContext<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class PreventDebuggerContext : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class PreventDebuggerContext
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As PreventDebuggerContext
```

**C++**<br />
``` C++
public ref class PreventDebuggerContext sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type PreventDebuggerContext =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The PreventDebuggerContext type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_PreventDebuggerContext__ctor">PreventDebuggerContext</a></td><td>
Initializes a new instance of the PreventDebuggerContext class.</td></tr></table>&nbsp;
<a href="#preventdebuggercontext-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_PreventDebuggerContext_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#preventdebuggercontext-class">Back to Top</a>

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
<a href="#preventdebuggercontext-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using preventDebugger As New PreventDebuggerContext()
    ' Insert your non-debuggable task here...
    Do While True
        Thread.Sleep(1000)
    Loop
End Using
```


## See Also


#### Reference
<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br />