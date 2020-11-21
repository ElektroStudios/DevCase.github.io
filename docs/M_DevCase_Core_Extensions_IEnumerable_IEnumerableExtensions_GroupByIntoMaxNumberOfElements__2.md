# IEnumerableExtensions.GroupByIntoMaxNumberOfElements(*T*, *TKey*) Method 
 

Groups the elements of a sequence according to a specified key selector function and takes the specified amount of elements of each group.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<IEnumerable<T>> GroupByIntoMaxNumberOfElements<T, TKey>(
	this IEnumerable<T> sender,
	int count,
	Func<T, TKey> keySelector
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GroupByIntoMaxNumberOfElements(Of T, TKey) ( 
	sender As IEnumerable(Of T),
	count As Integer,
	keySelector As Func(Of T, TKey)
) As IEnumerable(Of IEnumerable(Of T))
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of T)
Dim count As Integer
Dim keySelector As Func(Of T, TKey)
Dim returnValue As IEnumerable(Of IEnumerable(Of T))

returnValue = sender.GroupByIntoMaxNumberOfElements(count, 
	keySelector)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T, typename TKey>
static IEnumerable<IEnumerable<T>^>^ GroupByIntoMaxNumberOfElements(
	IEnumerable<T>^ sender, 
	int count, 
	Func<T, TKey>^ keySelector
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GroupByIntoMaxNumberOfElements : 
        sender : IEnumerable<'T> * 
        count : int * 
        keySelector : Func<'T, 'TKey> -> IEnumerable<IEnumerable<'T>> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(*T*)<br />The source collection.</dd><dt>count</dt><dd>Type: System.Int32<br />The maximum amount of elements per group.</dd><dt>keySelector</dt><dd>Type: System.Func(*T*, *TKey*)<br />A function to extract the key for each element.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the source elements.</dd><dt>TKey</dt><dd>The type of the key returned by *keySelector*.</dd></dl>

#### Return Value
Type: IEnumerable(IEnumerable(*T*))<br />The resulting IEnumerable(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim collection As IEnumerable(Of String) = {"1", "1", "22", "3", "333", "333"}
Dim groups As IEnumerable(Of IEnumerable(Of String)) = collection.GroupByIntoMaxNumberOfElements(2, Function(str As String) str.Length)

For index As Integer = 0 To (groups.Count - 1)
    For Each element As String In groups(index)
        Console.WriteLine("Group Index: {0}; Element: {1}", index, element)
    Next
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable Namespace</a><br />