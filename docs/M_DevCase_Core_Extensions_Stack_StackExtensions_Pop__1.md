# StackExtensions.Pop(*T*) Method 
 

Removes and returns the specified amount of objects from the top of the Stack(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Stack">DevCase.Core.Extensions.Stack</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static T[] Pop<T>(
	this Stack<T> sender,
	int amount
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Pop(Of T) ( 
	sender As Stack(Of T),
	amount As Integer
) As T()
```

**VB Usage**<br />
``` VB Usage
Dim sender As Stack(Of T)
Dim amount As Integer
Dim returnValue As T()

returnValue = sender.Pop(amount)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static array<T>^ Pop(
	Stack<T>^ sender, 
	int amount
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Pop : 
        sender : Stack<'T> * 
        amount : int -> 'T[] 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.Stack(*T*)<br />The source Stack(T).</dd><dt>amount</dt><dd>Type: System.Int32<br />The amount of items to pop.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: *T*[]<br />The objects removed from the top of the Stack(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Stack(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>amount</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim myStack As New Stack(Of String)
myStack.Push("1")
myStack.Push("2")
myStack.Push("3")

Dim items As String() = myStack.Pop(3)

MsgBox(String.Join("", items))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Stack_StackExtensions">StackExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Stack">DevCase.Core.Extensions.Stack Namespace</a><br />