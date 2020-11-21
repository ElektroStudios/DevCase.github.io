# IDictionaryExtensions.ToSortedDictionary(*TKey*, *TValue*) Method (IDictionary(*TKey*, *TValue*), IComparer(*TKey*))
 

Converts an IDictionary(TKey, TValue) to SortedDictionary(TKey, TValue).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IDictionary">DevCase.Core.Extensions.IDictionary</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static SortedDictionary<TKey, TValue> ToSortedDictionary<TKey, TValue>(
	this IDictionary<TKey, TValue> sender,
	IComparer<TKey> comparer
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToSortedDictionary(Of TKey, TValue) ( 
	sender As IDictionary(Of TKey, TValue),
	comparer As IComparer(Of TKey)
) As SortedDictionary(Of TKey, TValue)
```

**VB Usage**<br />
``` VB Usage
Dim sender As IDictionary(Of TKey, TValue)
Dim comparer As IComparer(Of TKey)
Dim returnValue As SortedDictionary(Of TKey, TValue)

returnValue = sender.ToSortedDictionary(comparer)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename TKey, typename TValue>
static SortedDictionary<TKey, TValue>^ ToSortedDictionary(
	IDictionary<TKey, TValue>^ sender, 
	IComparer<TKey>^ comparer
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToSortedDictionary : 
        sender : IDictionary<'TKey, 'TValue> * 
        comparer : IComparer<'TKey> -> SortedDictionary<'TKey, 'TValue> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IDictionary(*TKey*, *TValue*)<br />The source IDictionary(TKey, TValue).</dd><dt>comparer</dt><dd>Type: System.Collections.Generic.IComparer(*TKey*)<br />The IComparer(T) implementation to use when comparing keys, or null to use the default Comparer(T) for the type of the key"/>.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>TKey</dt><dd>\[Missing <typeparam name="TKey"/> documentation for "M:DevCase.Core.Extensions.IDictionary.IDictionaryExtensions.ToSortedDictionary``2(System.Collections.Generic.IDictionary{``0,``1},System.Collections.Generic.IComparer{``0})"\]</dd><dt>TValue</dt><dd>\[Missing <typeparam name="TValue"/> documentation for "M:DevCase.Core.Extensions.IDictionary.IDictionaryExtensions.ToSortedDictionary``2(System.Collections.Generic.IDictionary{``0,``1},System.Collections.Generic.IComparer{``0})"\]</dd></dl>

#### Return Value
Type: SortedDictionary(*TKey*, *TValue*)<br />The resulting SortedDictionary(TKey, TValue).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IDictionary(*TKey*, *TValue*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IDictionary_IDictionaryExtensions">IDictionaryExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_IDictionary_IDictionaryExtensions_ToSortedDictionary">ToSortedDictionary Overload</a><br /><a href="N_DevCase_Core_Extensions_IDictionary">DevCase.Core.Extensions.IDictionary Namespace</a><br />