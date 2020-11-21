# QueueExtensions.Reverse(*T*) Method 
 

Inverts the order of the elements of the source Queue(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Queue">DevCase.Core.Extensions.Queue</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Queue<T> Reverse<T>(
	this Queue<T> sender
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Reverse(Of T) ( 
	sender As Queue(Of T)
) As Queue(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim sender As Queue(Of T)
Dim returnValue As Queue(Of T)

returnValue = sender.Reverse()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static Queue<T>^ Reverse(
	Queue<T>^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Reverse : 
        sender : Queue<'T> -> Queue<'T> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.Queue(*T*)<br />The source Queue(T).</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Extensions.Queue.QueueExtensions.Reverse``1(System.Collections.Generic.Queue{``0})"\]</dd></dl>

#### Return Value
Type: Queue(*T*)<br />The resulting Queue(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Queue(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim myQueue As New Queue(Of String)
With myQueue
    .Enqueue("T")
    .Enqueue("E")
    .Enqueue("S")
    .Enqueue("T")
End With

myQueue = myQueue.Reverse

Do Until myQueue.Count = 0
    Console.WriteLine(myQueue.Dequeue)
Loop
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Queue_QueueExtensions">QueueExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Queue">DevCase.Core.Extensions.Queue Namespace</a><br />