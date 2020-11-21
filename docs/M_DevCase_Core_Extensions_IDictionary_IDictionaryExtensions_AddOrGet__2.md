# IDictionaryExtensions.AddOrGet(*TKey*, *TValue*) Method (IDictionary(*TKey*, *TValue*), *TKey*, Func(*TKey*, *TValue*))
 

Adds the specified key and value to the specified IDictionary(TKey, TValue) if the key does not already exist, and returns the value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IDictionary">DevCase.Core.Extensions.IDictionary</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static TValue AddOrGet<TKey, TValue>(
	this IDictionary<TKey, TValue> sender,
	TKey key,
	Func<TKey, TValue> valueFactory
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function AddOrGet(Of TKey, TValue) ( 
	sender As IDictionary(Of TKey, TValue),
	key As TKey,
	valueFactory As Func(Of TKey, TValue)
) As TValue
```

**VB Usage**<br />
``` VB Usage
Dim sender As IDictionary(Of TKey, TValue)
Dim key As TKey
Dim valueFactory As Func(Of TKey, TValue)
Dim returnValue As TValue

returnValue = sender.AddOrGet(key, 
	valueFactory)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename TKey, typename TValue>
static TValue AddOrGet(
	IDictionary<TKey, TValue>^ sender, 
	TKey key, 
	Func<TKey, TValue>^ valueFactory
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AddOrGet : 
        sender : IDictionary<'TKey, 'TValue> * 
        key : 'TKey * 
        valueFactory : Func<'TKey, 'TValue> -> 'TValue 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IDictionary(*TKey*, *TValue*)<br />The source IDictionary(TKey, TValue).</dd><dt>key</dt><dd>Type: *TKey*<br />The key to add.</dd><dt>valueFactory</dt><dd>Type: System.Func(*TKey*, *TValue*)<br />A function used to generate a value for the key.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>TKey</dt><dd>\[Missing <typeparam name="TKey"/> documentation for "M:DevCase.Core.Extensions.IDictionary.IDictionaryExtensions.AddOrGet``2(System.Collections.Generic.IDictionary{``0,``1},``0,System.Func{``0,``1})"\]</dd><dt>TValue</dt><dd>\[Missing <typeparam name="TValue"/> documentation for "M:DevCase.Core.Extensions.IDictionary.IDictionaryExtensions.AddOrGet``2(System.Collections.Generic.IDictionary{``0,``1},``0,System.Func{``0,``1})"\]</dd></dl>

#### Return Value
Type: *TValue*<br />The value.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IDictionary(*TKey*, *TValue*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IDictionary_IDictionaryExtensions">IDictionaryExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_IDictionary_IDictionaryExtensions_AddOrGet">AddOrGet Overload</a><br /><a href="N_DevCase_Core_Extensions_IDictionary">DevCase.Core.Extensions.IDictionary Namespace</a><br />