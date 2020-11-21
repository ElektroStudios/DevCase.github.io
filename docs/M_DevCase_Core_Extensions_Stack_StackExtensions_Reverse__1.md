# StackExtensions.Reverse(*T*) Method 
 

Inverts the order of the elements of the source Stack(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Stack">DevCase.Core.Extensions.Stack</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Stack<T> Reverse<T>(
	this Stack<T> sender
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Reverse(Of T) ( 
	sender As Stack(Of T)
) As Stack(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim sender As Stack(Of T)
Dim returnValue As Stack(Of T)

returnValue = sender.Reverse()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static Stack<T>^ Reverse(
	Stack<T>^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Reverse : 
        sender : Stack<'T> -> Stack<'T> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.Stack(*T*)<br />The source Stack(T).</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Extensions.Stack.StackExtensions.Reverse``1(System.Collections.Generic.Stack{``0})"\]</dd></dl>

#### Return Value
Type: Stack(*T*)<br />The resulting Stack(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Stack(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim myStack As New Stack(Of String)
With myStack
    .Push("T")
    .Push("E")
    .Push("S")
    .Push("T")
End With

myStack = myStack.Reverse

Do Until myStack.Count = 0
    Console.WriteLine(myStack.Pop)
Loop
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Stack_StackExtensions">StackExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Stack">DevCase.Core.Extensions.Stack Namespace</a><br />