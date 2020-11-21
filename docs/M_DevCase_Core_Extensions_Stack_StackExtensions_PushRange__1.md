# StackExtensions.PushRange(*T*) Method 
 

Inserts a range of objects in the incoming order at the top of the source Stack(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Stack">DevCase.Core.Extensions.Stack</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void PushRange<T>(
	this ref Stack<T> sender,
	T[] items
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub PushRange(Of T) ( 
	ByRef sender As Stack(Of T),
	items As T()
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As Stack(Of T)
Dim items As T()

sender.PushRange(items)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static void PushRange(
	Stack<T>^% sender, 
	array<T>^ items
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member PushRange : 
        sender : Stack<'T> byref * 
        items : 'T[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.Stack(*T*)<br />The source Stack(T).</dd><dt>items</dt><dd>Type: *T*[]<br />The items to push.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim myStack As New Stack(Of String)
myStack.PushRange({"T", "E", "S", "T"})

Do Until myStack.Count = 0
    Console.WriteLine(myStack.Pop)
Loop
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Stack_StackExtensions">StackExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Stack">DevCase.Core.Extensions.Stack Namespace</a><br />