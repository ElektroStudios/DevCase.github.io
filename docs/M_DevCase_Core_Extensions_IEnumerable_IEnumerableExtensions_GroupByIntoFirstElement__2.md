# IEnumerableExtensions.GroupByIntoFirstElement(*T*, *TKey*) Method 
 

Groups the elements of a sequence according to a specified key selector function and discards all the elements in each group except the first element.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<T> GroupByIntoFirstElement<T, TKey>(
	this IEnumerable<T> sender,
	Func<T, TKey> keySelector
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GroupByIntoFirstElement(Of T, TKey) ( 
	sender As IEnumerable(Of T),
	keySelector As Func(Of T, TKey)
) As IEnumerable(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of T)
Dim keySelector As Func(Of T, TKey)
Dim returnValue As IEnumerable(Of T)

returnValue = sender.GroupByIntoFirstElement(keySelector)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T, typename TKey>
static IEnumerable<T>^ GroupByIntoFirstElement(
	IEnumerable<T>^ sender, 
	Func<T, TKey>^ keySelector
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GroupByIntoFirstElement : 
        sender : IEnumerable<'T> * 
        keySelector : Func<'T, 'TKey> -> IEnumerable<'T> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(*T*)<br />The source collection.</dd><dt>keySelector</dt><dd>Type: System.Func(*T*, *TKey*)<br />A function to extract the key for each element.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the source elements.</dd><dt>TKey</dt><dd>The type of the key returned by *keySelector*.</dd></dl>

#### Return Value
Type: IEnumerable(*T*)<br />The resulting IEnumerable(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim collection As IEnumerable(Of String) = {"1", "1", "22", "3", "333", "333"}
collection = collection.GroupByIntoFirstElement(Function(str As String) str.Length)

For Each element As String In collection
    Console.WriteLine(element)
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable Namespace</a><br />