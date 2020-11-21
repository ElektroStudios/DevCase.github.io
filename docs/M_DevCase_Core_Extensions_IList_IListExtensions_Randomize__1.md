# IListExtensions.Randomize(*T*) Method 
 

Randomizes the elements of the source IList(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IList">DevCase.Core.Extensions.IList</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IList<T> Randomize<T>(
	this IList<T> sender
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Randomize(Of T) ( 
	sender As IList(Of T)
) As IList(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim sender As IList(Of T)
Dim returnValue As IList(Of T)

returnValue = sender.Randomize()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static IList<T>^ Randomize(
	IList<T>^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Randomize : 
        sender : IList<'T> -> IList<'T> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IList(*T*)<br />The source collection.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: IList(*T*)<br />IList(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IList(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim col As IList(Of Integer) From {1, 2, 3, 4, 5, 6, 7, 8, 9}
Debug.WriteLine(String.Join(", ", col.Randomize))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IList_IListExtensions">IListExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IList">DevCase.Core.Extensions.IList Namespace</a><br />