# IEnumerableExtensions.IndexOf(*T*) Method (IEnumerable(*T*), *T*, Int32, Int32)
 

Searches for the specified object and returns the zero-based index of the first occurrence within the entire IEnumerable(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int IndexOf<T>(
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
Public Shared Function IndexOf(Of T) ( 
	sender As IEnumerable(Of T),
	value As T,
	startIndex As Integer,
	count As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of T)
Dim value As T
Dim startIndex As Integer
Dim count As Integer
Dim returnValue As Integer

returnValue = sender.IndexOf(value, 
	startIndex, count)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static int IndexOf(
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
static member IndexOf : 
        sender : IEnumerable<'T> * 
        value : 'T * 
        startIndex : int * 
        count : int -> int 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(*T*)<br />The source IEnumerable(T).</dd><dt>value</dt><dd>Type: *T*<br />The object to locate in the IEnumerable(T).</dd><dt>startIndex</dt><dd>Type: System.Int32<br />The zero-based starting index of the search.</dd><dt>count</dt><dd>Type: System.Int32<br />The number of elements in the IEnumerable(T) to search.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Extensions.IEnumerable.IEnumerableExtensions.IndexOf``1(System.Collections.Generic.IEnumerable{``0},``0,System.Int32,System.Int32)"\]</dd></dl>

#### Return Value
Type: Int32<br />The zero-based index of the first occurrence of object within the entire IEnumerable(T), if found; otherwise, –1.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
MsgBox({1, 2, 3, 4, 5, 6, 7, 8, 9}.IndexOf(value:=1))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOf">IndexOf Overload</a><br /><a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable Namespace</a><br />