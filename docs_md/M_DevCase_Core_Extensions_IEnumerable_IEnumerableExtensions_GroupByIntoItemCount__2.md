# IEnumerableExtensions.GroupByIntoItemCount(*T*, *TKey*) Method 
 

Groups the elements of a sequence according to a specified key selector function and returns a Dictionary(TKey, TValue) dictionary on which {.key = element} and {.value = element count}.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Dictionary<TKey, int> GroupByIntoItemCount<T, TKey>(
	this IEnumerable<T> sequence,
	Func<T, TKey> keySelector
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GroupByIntoItemCount(Of T, TKey) ( 
	sequence As IEnumerable(Of T),
	keySelector As Func(Of T, TKey)
) As Dictionary(Of TKey, Integer)
```

**VB Usage**<br />
``` VB Usage
Dim sequence As IEnumerable(Of T)
Dim keySelector As Func(Of T, TKey)
Dim returnValue As Dictionary(Of TKey, Integer)

returnValue = sequence.GroupByIntoItemCount(keySelector)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T, typename TKey>
static Dictionary<TKey, int>^ GroupByIntoItemCount(
	IEnumerable<T>^ sequence, 
	Func<T, TKey>^ keySelector
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GroupByIntoItemCount : 
        sequence : IEnumerable<'T> * 
        keySelector : Func<'T, 'TKey> -> Dictionary<'TKey, int> 

```


#### Parameters
&nbsp;<dl><dt>sequence</dt><dd>Type: System.Collections.Generic.IEnumerable(*T*)<br />The source sequence.</dd><dt>keySelector</dt><dd>Type: System.Func(*T*, *TKey*)<br />A function to extract the key for each element.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the source elements.</dd><dt>TKey</dt><dd>The type of the key returned by *keySelector*.</dd></dl>

#### Return Value
Type: Dictionary(*TKey*, Int32)<br />The resulting Dictionary(TKey, TValue).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim sequence As IEnumerable(Of String) = {"a", "A", "c", "d", "b", "b", "b", "b", "b"}
Dim groups As Dictionary(Of String, Integer) = sequence.GroupByIntoItemCount(Function(str As String) str)

For Each group As KeyValuePair(Of String, Integer) In groups
    Console.WriteLine($"{NameOf(group.Key)}: {group.Key}; {NameOf(group.Value)}: {group.Value}")
Next group
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable Namespace</a><br />