# IGroupingExtensions.JoinByFirstGroupElement(*T*, *TKey*) Method (IEnumerable(IGrouping(*TKey*, *T*)))
 

Takes the first element of each group and joins them into a new IEnumerable(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IGrouping">DevCase.Core.Extensions.IGrouping</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<T> JoinByFirstGroupElement<T, TKey>(
	this IEnumerable<IGrouping<TKey, T>> sender
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function JoinByFirstGroupElement(Of T, TKey) ( 
	sender As IEnumerable(Of IGrouping(Of TKey, T))
) As IEnumerable(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of IGrouping(Of TKey, T))
Dim returnValue As IEnumerable(Of T)

returnValue = sender.JoinByFirstGroupElement()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T, typename TKey>
static IEnumerable<T>^ JoinByFirstGroupElement(
	IEnumerable<IGrouping<TKey, T>^>^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member JoinByFirstGroupElement : 
        sender : IEnumerable<IGrouping<'TKey, 'T>> -> IEnumerable<'T> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(IGrouping(*TKey*, *T*))<br />The source collection.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the source elements.</dd><dt>TKey</dt><dd>The type of the source <a href="N_DevCase_Core_Extensions_IGrouping">DevCase.Core.Extensions.IGrouping</a> key.</dd></dl>

#### Return Value
Type: IEnumerable(*T*)<br />The resulting IEnumerable(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(IGrouping(*TKey*, *T*)). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim collection As IEnumerable(Of String) = {"1", "1", "22", "3", "333", "333"}
Dim groups As IEnumerable(Of IGrouping(Of Integer, String)) = collection.GroupBy(Function(str As String) str.Length)
Dim newCollection As IEnumerable(Of String) = groups.JoinByFirstGroupElement()

For Each element As String In newCollection
    Console.WriteLine(element)
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IGrouping_IGroupingExtensions">IGroupingExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_IGrouping_IGroupingExtensions_JoinByFirstGroupElement">JoinByFirstGroupElement Overload</a><br /><a href="N_DevCase_Core_Extensions_IGrouping">DevCase.Core.Extensions.IGrouping Namespace</a><br />