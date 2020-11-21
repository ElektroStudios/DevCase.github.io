# QueueExtensions.EnqueueRange(*T*) Method 
 

Adds a range of objects in the incoming order to the end of the source Queue(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Queue">DevCase.Core.Extensions.Queue</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void EnqueueRange<T>(
	this ref Queue<T> sender,
	T[] items
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub EnqueueRange(Of T) ( 
	ByRef sender As Queue(Of T),
	items As T()
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As Queue(Of T)
Dim items As T()

sender.EnqueueRange(items)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static void EnqueueRange(
	Queue<T>^% sender, 
	array<T>^ items
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member EnqueueRange : 
        sender : Queue<'T> byref * 
        items : 'T[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.Queue(*T*)<br />The source Queue(T).</dd><dt>items</dt><dd>Type: *T*[]<br />The items to enqueue.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim myQueue As New Queue(Of String)
myQueue.EnqueueRange({"T", "E", "S", "T"})

Do Until myQueue.Count = 0
    Console.WriteLine(myStack.Dequeue)
Loop
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Queue_QueueExtensions">QueueExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Queue">DevCase.Core.Extensions.Queue Namespace</a><br />