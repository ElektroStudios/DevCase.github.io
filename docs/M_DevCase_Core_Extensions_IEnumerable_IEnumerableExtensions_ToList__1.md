# IEnumerableExtensions.ToList(*T*) Method 
 

Creates a List(T) from an IEnumerable(T) using the specified transform function.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static List<T> ToList<T>(
	this IEnumerable<T> sender,
	Func<T, bool> predicate
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToList(Of T) ( 
	sender As IEnumerable(Of T),
	predicate As Func(Of T, Boolean)
) As List(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of T)
Dim predicate As Func(Of T, Boolean)
Dim returnValue As List(Of T)

returnValue = sender.ToList(predicate)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static List<T>^ ToList(
	IEnumerable<T>^ sender, 
	Func<T, bool>^ predicate
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToList : 
        sender : IEnumerable<'T> * 
        predicate : Func<'T, bool> -> List<'T> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(*T*)<br />The source IEnumerable(T).</dd><dt>predicate</dt><dd>Type: System.Func(*T*, Boolean)<br />A transform function to apply to each element.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type</dd></dl>

#### Return Value
Type: List(*T*)<br />The resulting List(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim col As IEnumerable(Of Integer) = Enumerable.Range(1, 10)
Dim list As List(Of Integer) = col.ToList(Function(i As Integer) i > 5)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable Namespace</a><br />