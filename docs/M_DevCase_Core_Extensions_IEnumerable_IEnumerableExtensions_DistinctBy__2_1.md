# IEnumerableExtensions.DistinctBy(*TSource*, *TKey*) Method (IEnumerable(*TSource*), Func(*TSource*, *TKey*), IEqualityComparer(*TKey*))
 

Returns distinct elements from a sequence by using a specified key selector and equality comparer to compare values.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<TSource> DistinctBy<TSource, TKey>(
	this IEnumerable<TSource> sequence,
	Func<TSource, TKey> selector,
	IEqualityComparer<TKey> comparer
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function DistinctBy(Of TSource, TKey) ( 
	sequence As IEnumerable(Of TSource),
	selector As Func(Of TSource, TKey),
	comparer As IEqualityComparer(Of TKey)
) As IEnumerable(Of TSource)
```

**VB Usage**<br />
``` VB Usage
Dim sequence As IEnumerable(Of TSource)
Dim selector As Func(Of TSource, TKey)
Dim comparer As IEqualityComparer(Of TKey)
Dim returnValue As IEnumerable(Of TSource)

returnValue = sequence.DistinctBy(selector, 
	comparer)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename TSource, typename TKey>
static IEnumerable<TSource>^ DistinctBy(
	IEnumerable<TSource>^ sequence, 
	Func<TSource, TKey>^ selector, 
	IEqualityComparer<TKey>^ comparer
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member DistinctBy : 
        sequence : IEnumerable<'TSource> * 
        selector : Func<'TSource, 'TKey> * 
        comparer : IEqualityComparer<'TKey> -> IEnumerable<'TSource> 

```


#### Parameters
&nbsp;<dl><dt>sequence</dt><dd>Type: System.Collections.Generic.IEnumerable(*TSource*)<br />The sequence to remove duplicate elements from.</dd><dt>selector</dt><dd>Type: System.Func(*TSource*, *TKey*)<br />A transform function to apply to each element.</dd><dt>comparer</dt><dd>Type: System.Collections.Generic.IEqualityComparer(*TKey*)<br />An IEqualityComparer(T) to compare keys.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>TSource</dt><dd>The type of the sequence.</dd><dt>TKey</dt><dd>The type of the key to compare.</dd></dl>

#### Return Value
Type: IEnumerable(*TSource*)<br />The resulting IEnumerable(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(*TSource*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_DistinctBy">DistinctBy Overload</a><br /><a href="N_DevCase_Core_Extensions_IEnumerable">DevCase.Core.Extensions.IEnumerable Namespace</a><br />