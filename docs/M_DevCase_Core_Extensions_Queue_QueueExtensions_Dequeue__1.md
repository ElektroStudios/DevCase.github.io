# QueueExtensions.Dequeue(*T*) Method 
 

Removes and returns the specified amount of objects from the beginning of the Queue(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Queue">DevCase.Core.Extensions.Queue</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static T[] Dequeue<T>(
	this Queue<T> sender,
	int amount
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Dequeue(Of T) ( 
	sender As Queue(Of T),
	amount As Integer
) As T()
```

**VB Usage**<br />
``` VB Usage
Dim sender As Queue(Of T)
Dim amount As Integer
Dim returnValue As T()

returnValue = sender.Dequeue(amount)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static array<T>^ Dequeue(
	Queue<T>^ sender, 
	int amount
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Dequeue : 
        sender : Queue<'T> * 
        amount : int -> 'T[] 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.Queue(*T*)<br />The source Queue(T).</dd><dt>amount</dt><dd>Type: System.Int32<br />The amount of items to pop.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: *T*[]<br />The objects removed from the beginning of the Queue(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Queue(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>amount</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim myQueue As New Queue(Of String)
myQueue.Enqueue("1")
myQueue.Enqueue("2")
myQueue.Enqueue("3")

Dim items As String() = myQueue.Dequeue(3)

MsgBox(String.Join(",", items))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Queue_QueueExtensions">QueueExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Queue">DevCase.Core.Extensions.Queue Namespace</a><br />