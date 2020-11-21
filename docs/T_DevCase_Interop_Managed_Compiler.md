# Compiler Class
 

Encapsulates a CodeDom provider compiler.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Interop.Managed.Compiler<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Interop_Managed_CSharpCompiler">DevCase.Interop.Managed.CSharpCompiler</a><br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Interop_Managed_VisualBasicCompiler">DevCase.Interop.Managed.VisualBasicCompiler</a><br />
**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public abstract class Compiler : IDisposable
```

**VB**<br />
``` VB
Public MustInherit Class Compiler
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As Compiler
```

**C++**<br />
``` C++
public ref class Compiler abstract : IDisposable
```

**F#**<br />
``` F#
[<AbstractClassAttribute>]
type Compiler =  
    class
        interface IDisposable
    end
```

The Compiler type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Managed_Compiler__ctor">Compiler</a></td><td>
Initializes a new instance of the Compiler class.</td></tr></table>&nbsp;
<a href="#compiler-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_Compiler_Compilersettings">Compilersettings</a></td><td>
Gets or sets the settings of this Compiler.</td></tr></table>&nbsp;
<a href="#compiler-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Managed_Compiler_CompileFromFile">CompileFromFile</a></td><td>
Compiles a .NET assembly from the specified source code file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Managed_Compiler_CompileFromString">CompileFromString</a></td><td>
Compiles a .NET assembly from the specified source code string.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Managed_Compiler_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#compiler-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Interop_Managed_Compiler_CompilerWorkDone">CompilerWorkDone</a></td><td>
Occurs when the compiler finishes.</td></tr></table>&nbsp;
<a href="#compiler-class">Back to Top</a>

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
<a href="#compiler-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />