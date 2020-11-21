# IEnumerableExtensions.IndexOfAll(*T*) Method (IEnumerable(*T*), IEnumerable(*T*))
 

Searches for the specified object pattern and returns the zero-based indices of all the occurrence within the entire IEnumerable(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<int> IndexOfAll<T>(
	this IEnumerable<T> sender,
	IEnumerable<T> pattern
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IndexOfAll(Of T) ( 
	sender As IEnumerable(Of T),
	pattern As IEnumerable(Of T)
) As IEnumerable(Of Integer)
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of T)
Dim pattern As IEnumerable(Of T)
Dim returnValue As IEnumerable(Of Integer)

returnValue = sender.IndexOfAll(pattern)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static IEnumerable<int>^ IndexOfAll(
	IEnumerable<T>^ sender, 
	IEnumerable<T>^ pattern
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IndexOfAll : 
        sender : IEnumerable<'T> * 
        pattern : IEnumerable<'T> -> IEnumerable<int> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(*T*)<br />The source IEnumerable(T).</dd><dt>pattern</dt><dd>Type: System.Collections.Generic.IEnumerable(*T*)<br />The object pattern to locate in the IEnumerable(T).</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Extensions.IEnumerable.IEnumerableExtensions.IndexOfAll``1(System.Collections.Generic.IEnumerable{``0},System.Collections.Generic.IEnumerable{``0})"\]</dd></dl>

#### Return Value
Type: IEnumerable(Int32)<br />The zero-based index of all the occurrences of object pattern within the entire IEnumerable(T), if found; otherwise, a null reference (`Nothing` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>index;Value equals or bigger than 0 is required. or count;Value bigger than 0 is required. or count;Value equals or bigger than the pattern length is required.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
MsgBox(String.Join(", ", {0, 1, 2, 3, 4, 5, 6, 5, 5, 9}.IndexOfAll(pattern:={5, 5})))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOfAll">IndexOfAll Overload</a><br /><a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable Namespace</a><br />