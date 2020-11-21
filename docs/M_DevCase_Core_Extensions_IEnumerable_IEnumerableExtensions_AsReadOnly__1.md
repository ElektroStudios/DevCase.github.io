# IEnumerableExtensions.AsReadOnly(*T*) Method 
 

Returns a read-only ReadOnlyCollection(T) wrapper for the specified collection.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static ReadOnlyCollection<T> AsReadOnly<T>(
	this IEnumerable<T> collection
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function AsReadOnly(Of T) ( 
	collection As IEnumerable(Of T)
) As ReadOnlyCollection(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim collection As IEnumerable(Of T)
Dim returnValue As ReadOnlyCollection(Of T)

returnValue = collection.AsReadOnly()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static ReadOnlyCollection<T>^ AsReadOnly(
	IEnumerable<T>^ collection
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AsReadOnly : 
        collection : IEnumerable<'T> -> ReadOnlyCollection<'T> 

```


#### Parameters
&nbsp;<dl><dt>collection</dt><dd>Type: System.Collections.Generic.IEnumerable(*T*)<br />The source collection.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the collection.</dd></dl>

#### Return Value
Type: ReadOnlyCollection(*T*)<br />The resulting ReadOnlyCollection(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable Namespace</a><br />