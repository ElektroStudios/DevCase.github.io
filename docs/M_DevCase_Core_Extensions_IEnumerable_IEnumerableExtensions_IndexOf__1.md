# IEnumerableExtensions.IndexOf(*T*) Method (IEnumerable(*T*), IEnumerable(*T*))
 

Searches for the specified object pattern and returns the zero-based index of the first occurrence within the entire IEnumerable(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int IndexOf<T>(
	this IEnumerable<T> sender,
	IEnumerable<T> pattern
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IndexOf(Of T) ( 
	sender As IEnumerable(Of T),
	pattern As IEnumerable(Of T)
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of T)
Dim pattern As IEnumerable(Of T)
Dim returnValue As Integer

returnValue = sender.IndexOf(pattern)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static int IndexOf(
	IEnumerable<T>^ sender, 
	IEnumerable<T>^ pattern
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IndexOf : 
        sender : IEnumerable<'T> * 
        pattern : IEnumerable<'T> -> int 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(*T*)<br />The source IEnumerable(T).</dd><dt>pattern</dt><dd>Type: System.Collections.Generic.IEnumerable(*T*)<br />The object pattern to locate in the IEnumerable(T).</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Extensions.IEnumerable.IEnumerableExtensions.IndexOf``1(System.Collections.Generic.IEnumerable{``0},System.Collections.Generic.IEnumerable{``0})"\]</dd></dl>

#### Return Value
Type: Int32<br />The zero-based index of the first occurrence of object pattern within the entire IEnumerable(T), if found; otherwise, –1.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
MsgBox({0, 1, 2, 3, 4, 5, 6, 7, 8, 9}.IndexOf(pattern:={5, 6, 7}))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOf">IndexOf Overload</a><br /><a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable Namespace</a><br />