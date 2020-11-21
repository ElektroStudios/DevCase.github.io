# IEnumerableExtensions.IndexOfAll(*T*) Method (IEnumerable(*T*), *T*, Int32, Int32)
 

Searches for the specified object and returns the zero-based indices of all the occurrence within the entire IEnumerable(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<int> IndexOfAll<T>(
	this IEnumerable<T> sender,
	T value,
	int startIndex,
	int count
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IndexOfAll(Of T) ( 
	sender As IEnumerable(Of T),
	value As T,
	startIndex As Integer,
	count As Integer
) As IEnumerable(Of Integer)
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of T)
Dim value As T
Dim startIndex As Integer
Dim count As Integer
Dim returnValue As IEnumerable(Of Integer)

returnValue = sender.IndexOfAll(value, 
	startIndex, count)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static IEnumerable<int>^ IndexOfAll(
	IEnumerable<T>^ sender, 
	T value, 
	int startIndex, 
	int count
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IndexOfAll : 
        sender : IEnumerable<'T> * 
        value : 'T * 
        startIndex : int * 
        count : int -> IEnumerable<int> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(*T*)<br />The source IEnumerable(T).</dd><dt>value</dt><dd>Type: *T*<br />The object to locate in the IEnumerable(T).</dd><dt>startIndex</dt><dd>Type: System.Int32<br />The zero-based starting index of the search.</dd><dt>count</dt><dd>Type: System.Int32<br />The number of elements in the IEnumerable(T) to search.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Extensions.IEnumerable.IEnumerableExtensions.IndexOfAll``1(System.Collections.Generic.IEnumerable{``0},``0,System.Int32,System.Int32)"\]</dd></dl>

#### Return Value
Type: IEnumerable(Int32)<br />The zero-based index of all the occurrences of object within the entire IEnumerable(T), if found; otherwise, a null reference (`Nothing` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>index;Value equals or bigger than 0 is required. or count;Value bigger than 0 is required. or count;Value equals or bigger than the pattern length is required.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
MsgBox(String.Join(", ", {0, 1, 2, 3, 4, 5, 6, 5, 5, 9}.IndexOfAll(value:=5, index:=5, count:=4)))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOfAll">IndexOfAll Overload</a><br /><a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable Namespace</a><br />