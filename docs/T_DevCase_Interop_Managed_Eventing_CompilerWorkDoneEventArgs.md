# CompilerWorkDoneEventArgs Class
 

Defines the event-data of a <a href="E_DevCase_Interop_Managed_Compiler_CompilerWorkDone">CompilerWorkDone</a> event.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.EventArgs<br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Interop.Managed.Eventing.CompilerWorkDoneEventArgs<br />
**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Eventing">DevCase.Interop.Managed.Eventing</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class CompilerWorkDoneEventArgs : EventArgs
```

**VB**<br />
``` VB
Public NotInheritable Class CompilerWorkDoneEventArgs
	Inherits EventArgs
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerWorkDoneEventArgs
```

**C++**<br />
``` C++
public ref class CompilerWorkDoneEventArgs sealed : public EventArgs
```

**F#**<br />
``` F#
[<SealedAttribute>]
type CompilerWorkDoneEventArgs =  
    class
        inherit EventArgs
    end
```

The CompilerWorkDoneEventArgs type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs__ctor">CompilerWorkDoneEventArgs</a></td><td>
Initializes a new instance of the CompilerWorkDoneEventArgs class.</td></tr></table>&nbsp;
<a href="#compilerworkdoneeventargs-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs_CodeDomProvider">CodeDomProvider</a></td><td>
Gets the <a href="P_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs_CodeDomProvider">CodeDomProvider</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs_CompileErrors">CompileErrors</a></td><td>
Gets the compiler errors.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs_CompilerParameters">CompilerParameters</a></td><td>
Gets the compiler parameters used to build the target file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs_CompilerWarnings">CompilerWarnings</a></td><td>
Gets the compiler warnings.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs_SourceCode">SourceCode</a></td><td>
Gets the source code string. Only when a string is used to compile.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs_SourceFilePath">SourceFilePath</a></td><td>
Gets the source filepath. Only when a file is used to compile.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs_TargetFilePath">TargetFilePath</a></td><td>
Gets the target .NET assembly filepath.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs_TempDirectoryPath">TempDirectoryPath</a></td><td>
Gets the temporary files path used for the compiler.</td></tr></table>&nbsp;
<a href="#compilerworkdoneeventargs-class">Back to Top</a>

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
<a href="#compilerworkdoneeventargs-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Managed_Eventing">DevCase.Interop.Managed.Eventing Namespace</a><br />