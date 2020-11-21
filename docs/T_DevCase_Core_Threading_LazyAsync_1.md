# LazyAsync(*T*) Class
 

Provides support for asynchronous lazy initialization.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.Threading.LazyAsync(T)<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Threading">DevCase.Core.Threading</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComVisibleAttribute(false)]
public sealed class LazyAsync<T> : IDisposable

```

**VB**<br />
``` VB
<ComVisibleAttribute(false)>
Public NotInheritable Class LazyAsync(Of T)
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As LazyAsync(Of T)
```

**C++**<br />
``` C++
[ComVisibleAttribute(false)]
generic<typename T>
public ref class LazyAsync sealed : IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ComVisibleAttribute(false)>]
type LazyAsync<'T> =  
    class
        interface IDisposable
    end
```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of object that is being initialized.</dd></dl>&nbsp;
The LazyAsync(T) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Threading_LazyAsync_1__ctor">LazyAsync(T)(Func(T))</a></td><td>
Initializes a new instance of the LazyAsync(T) class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Threading_LazyAsync_1__ctor_1">LazyAsync(T)(Func(T), Boolean)</a></td><td>
Initializes a new instance of the LazyAsync(T) class.</td></tr></table>&nbsp;
<a href="#lazyasync(*t*)-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Threading_LazyAsync_1_IsValueCreated">IsValueCreated</a></td><td>
Gets a value that indicates whether a value has been created for this LazyAsync(T).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Threading_LazyAsync_1_Value">Value</a></td><td>
Gets the lazily initialized value of the current LazyAsync(T). 

 If the value have not been initialized, blocks the calling thread until the value get initialized. 

 If during initialization an exception have been thrown, it will wrapped into AggregateException and rethrowned on accessing this property.</td></tr></table>&nbsp;
<a href="#lazyasync(*t*)-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Threading_LazyAsync_1_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Threading_LazyAsync_1_InitializeAsync">InitializeAsync</a></td><td>
Asynchronously initializes the <a href="P_DevCase_Core_Threading_LazyAsync_1_Value">Value</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Threading_LazyAsync_1_ToString">ToString</a></td><td>
Creates and returns a string representation of the <a href="P_DevCase_Core_Threading_LazyAsync_1_Value">Value</a> property for this instance.
 (Overrides Object.ToString().)</td></tr></table>&nbsp;
<a href="#lazyasync(*t*)-class">Back to Top</a>

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
<a href="#lazyasync(*t*)-class">Back to Top</a>

## Remarks
Based on this code: <a href="https://16handles.wordpress.com/2011/04/21/asynchronous-lazy-initialization/" target="_blank">https://16handles.wordpress.com/2011/04/21/asynchronous-lazy-initialization/</a>

 Alternative implementation: <a href="http://blogs.msdn.com/b/pfxteam/archive/2011/01/15/10116210.aspx" target="_blank">http://blogs.msdn.com/b/pfxteam/archive/2011/01/15/10116210.aspx</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Private Shared lazyObj As New LazyAsync(Of Object)(Function() "Hello World")

Private Sub Test()

    Console.WriteLine("initializing the lazy object...")
    lazyObj.InitializeAsync()

    Console.WriteLine("Doing some work...")
    For x As Integer = 0 To 10
        Thread.Sleep(100)
    Next

    Console.WriteLine("Accessing the lazy object value...")
    Dim result As Object = lazyObj.Value

    Console.WriteLine(String.Format("The value is: {0}", result.ToString()))

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_Core_Threading">DevCase.Core.Threading Namespace</a><br />