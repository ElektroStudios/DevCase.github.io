# FixedQueue(*T*) Class
 

Represents a Queue(T) with a fixed capacity.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Collections.Generic.Queue(*T*)<br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Collections.FixedQueue(T)<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("FixedQueue")]
public sealed class FixedQueue<T> : Queue<T>

```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("FixedQueue")>
Public NotInheritable Class FixedQueue(Of T)
	Inherits Queue(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FixedQueue(Of T)
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"FixedQueue")]
generic<typename T>
public ref class FixedQueue sealed : public Queue<T>
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("FixedQueue")>]
type FixedQueue<'T> =  
    class
        inherit Queue<'T>
    end
```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the queue items.</dd></dl>&nbsp;
The FixedQueue(T) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_FixedQueue_1__ctor">FixedQueue(T)</a></td><td>
Initializes a new instance of the FixedQueue(T) class.</td></tr></table>&nbsp;
<a href="#fixedqueue(*t*)-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_FixedQueue_1_FreeSlots">FreeSlots</a></td><td>
Gets the amount of free slots onto this FixedQueue(T).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_FixedQueue_1_IsEmpty">IsEmpty</a></td><td>
Gets a value indicating whether this FixedQueue(T) is empty.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_FixedQueue_1_IsFull">IsFull</a></td><td>
Gets a value indicating whether this FixedQueue(T) is full.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_FixedQueue_1_MaxCapacity">MaxCapacity</a></td><td>
Gets the maximum capacity of this FixedQueue(T), bottom items beyond the specified capacity are discarded when a new item is pushed.</td></tr></table>&nbsp;
<a href="#fixedqueue(*t*)-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_FixedQueue_1_Enqueue">Enqueue</a></td><td>
Adds an object to the end of this FixedQueue(T).</td></tr></table>&nbsp;
<a href="#fixedqueue(*t*)-class">Back to Top</a>

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
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Queue_QueueExtensions_Dequeue__1">Dequeue(T)</a></td><td>
Removes and returns the specified amount of objects from the beginning of the Queue(T).
 (Defined by <a href="T_DevCase_Core_Extensions_Queue_QueueExtensions">QueueExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Queue_QueueExtensions_Peek__1">Peek(T)</a></td><td>
Returns the specified amount of objects from the beginning of the Queue(T).
 (Defined by <a href="T_DevCase_Core_Extensions_Queue_QueueExtensions">QueueExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Queue_QueueExtensions_Reverse__1">Reverse(T)</a></td><td>
Inverts the order of the elements of the source Queue(T).
 (Defined by <a href="T_DevCase_Core_Extensions_Queue_QueueExtensions">QueueExtensions</a>.)</td></tr></table>&nbsp;
<a href="#fixedqueue(*t*)-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim queue As New FixedQueue(Of Integer)(maxCapacity:=5)

For x As Integer = 0 To 10
    queue.Enqueue(x)
Next

For Each value As Integer In queue
    Console.WriteLine(value)
Next
```


## See Also


#### Reference
<a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />