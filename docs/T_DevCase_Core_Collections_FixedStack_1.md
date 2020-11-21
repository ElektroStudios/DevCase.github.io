# FixedStack(*T*) Class
 

Represents a Stack(T) with a fixed capacity.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Collections.Generic.Stack(*T*)<br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Collections.FixedStack(T)<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("FixedStack")]
public sealed class FixedStack<T> : Stack<T>

```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("FixedStack")>
Public NotInheritable Class FixedStack(Of T)
	Inherits Stack(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FixedStack(Of T)
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"FixedStack")]
generic<typename T>
public ref class FixedStack sealed : public Stack<T>
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("FixedStack")>]
type FixedStack<'T> =  
    class
        inherit Stack<'T>
    end
```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the stack items.</dd></dl>&nbsp;
The FixedStack(T) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_FixedStack_1__ctor">FixedStack(T)</a></td><td>
Initializes a new instance of the FixedStack(T) class.</td></tr></table>&nbsp;
<a href="#fixedstack(*t*)-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_FixedStack_1_FreeSlots">FreeSlots</a></td><td>
Gets the amount of free slots onto this FixedStack(T).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_FixedStack_1_IsEmpty">IsEmpty</a></td><td>
Gets a value indicating whether this FixedStack(T) is empty.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_FixedStack_1_IsFull">IsFull</a></td><td>
Gets a value indicating whether this FixedStack(T) is full.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_FixedStack_1_MaxCapacity">MaxCapacity</a></td><td>
Gets the maximum capacity of this FixedStack(T), bottom items beyond the specified capacity are discarded when a new item is pushed.</td></tr></table>&nbsp;
<a href="#fixedstack(*t*)-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_FixedStack_1_Push">Push</a></td><td>
Inserts an object at the top of this FixedStack(T).</td></tr></table>&nbsp;
<a href="#fixedstack(*t*)-class">Back to Top</a>

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
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Stack_StackExtensions_Peek__1">Peek(T)</a></td><td>
Returns the specified amount of objects from the top of the Stack(T).
 (Defined by <a href="T_DevCase_Core_Extensions_Stack_StackExtensions">StackExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Stack_StackExtensions_Pop__1">Pop(T)</a></td><td>
Removes and returns the specified amount of objects from the top of the Stack(T).
 (Defined by <a href="T_DevCase_Core_Extensions_Stack_StackExtensions">StackExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Stack_StackExtensions_Reverse__1">Reverse(T)</a></td><td>
Inverts the order of the elements of the source Stack(T).
 (Defined by <a href="T_DevCase_Core_Extensions_Stack_StackExtensions">StackExtensions</a>.)</td></tr></table>&nbsp;
<a href="#fixedstack(*t*)-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim stack As New FixedStack(Of Integer)(maxCapacity:=5)

For x As Integer = 0 To 10
    stack.Push(x)
Next

For Each value As Integer In stack
    Console.WriteLine(value)
Next
```


## See Also


#### Reference
<a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />