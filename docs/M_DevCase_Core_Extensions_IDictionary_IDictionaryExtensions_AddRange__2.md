# IDictionaryExtensions.AddRange(*TKey*, *TValue*) Method 
 

Adds a range of elements to the source IDictionary(TKey, TValue).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IDictionary">DevCase.Core.Extensions.IDictionary</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void AddRange<TKey, TValue>(
	this ref IDictionary<TKey, TValue> self,
	KeyValuePair<TKey, TValue>[] items
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub AddRange(Of TKey, TValue) ( 
	ByRef self As IDictionary(Of TKey, TValue),
	items As KeyValuePair(Of TKey, TValue)()
)
```

**VB Usage**<br />
``` VB Usage
Dim self As IDictionary(Of TKey, TValue)
Dim items As KeyValuePair(Of TKey, TValue)()

self.AddRange(items)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename TKey, typename TValue>
static void AddRange(
	IDictionary<TKey, TValue>^% self, 
	array<KeyValuePair<TKey, TValue>>^ items
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AddRange : 
        self : IDictionary<'TKey, 'TValue> byref * 
        items : KeyValuePair<'TKey, 'TValue>[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>self</dt><dd>Type: System.Collections.Generic.IDictionary(*TKey*, *TValue*)<br />The source IDictionary(TKey, TValue).</dd><dt>items</dt><dd>Type: System.Collections.Generic.KeyValuePair(*TKey*, *TValue*)[]<br />The items to add.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>TKey</dt><dd>\[Missing <typeparam name="TKey"/> documentation for "M:DevCase.Core.Extensions.IDictionary.IDictionaryExtensions.AddRange``2(System.Collections.Generic.IDictionary{``0,``1}@,System.Collections.Generic.KeyValuePair{``0,``1}[])"\]</dd><dt>TValue</dt><dd>\[Missing <typeparam name="TValue"/> documentation for "M:DevCase.Core.Extensions.IDictionary.IDictionaryExtensions.AddRange``2(System.Collections.Generic.IDictionary{``0,``1}@,System.Collections.Generic.KeyValuePair{``0,``1}[])"\]</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IDictionary_IDictionaryExtensions">IDictionaryExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IDictionary">DevCase.Core.Extensions.IDictionary Namespace</a><br />