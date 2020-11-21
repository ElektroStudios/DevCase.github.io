# ProfillingUtil Class
 

Contains profilling and unit testing related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Diagnostics.Tools.ProfillingUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ProfillingUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class ProfillingUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProfillingUtil
```

**C++**<br />
``` C++
public ref class ProfillingUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ProfillingUtil =  
    class
        inherit AestheticObject
    end
```

The ProfillingUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_ProfillingUtil_CollectGarbage">CollectGarbage</a></td><td>
Invokes the GarbageCollector to occur immediately.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_ProfillingUtil_FlushMemory">FlushMemory()</a></td><td>
Flushes the memory of the current process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_ProfillingUtil_FlushMemory_1">FlushMemory(IntPtr)</a></td><td>
Flushes the memory of the current process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_ProfillingUtil_InlineAssignHelper">InlineAssignHelper(Object, Object)</a></td><td>
Helper function that assigns *value* to *refTarget*, then returns *value*.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_ProfillingUtil_InlineAssignHelper__1">InlineAssignHelper(T)(T, T)</a></td><td>
Helper function that assigns *value* to *refTarget*, then returns *value*.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_ProfillingUtil_InvokeTimes">InvokeTimes(Int32, Action)</a></td><td>
Invokes an Action for the specified amount of times.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_ProfillingUtil_InvokeTimes__1">InvokeTimes(T)(Int32, Func(T))</a></td><td>
Invokes a Func(TResult) for the specified amount of times.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_ProfillingUtil_SwapObjects">SwapObjects(Object, Object)</a></td><td>
Swaps the given objects.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_ProfillingUtil_SwapObjects__1">SwapObjects(T)(T, T)</a></td><td>
Swaps the given objects.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_ProfillingUtil_TestSuccess">TestSuccess</a></td><td>
Tests the execution of a Action then returns a value that indicates whether the execution was successful.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_ProfillingUtil_TestSuccessAsync">TestSuccessAsync</a></td><td>
Tests the execution of a Action then returns a value that indicates whether the execution was successful.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_ProfillingUtil_TestTime">TestTime</a></td><td>
Tests the execution of a Action and measures the elapsed time.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Diagnostics_Tools_ProfillingUtil_TestTimeAsync">TestTimeAsync</a></td><td>
Asynchronously tests the execution of a Action and measures the elapsed time.</td></tr></table>&nbsp;
<a href="#profillingutil-class">Back to Top</a>

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
<a href="#profillingutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />