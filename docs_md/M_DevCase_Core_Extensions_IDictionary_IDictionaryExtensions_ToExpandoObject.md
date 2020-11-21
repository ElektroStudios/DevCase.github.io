# IDictionaryExtensions.ToExpandoObject Method 
 

Converts an IDictionary(TKey, TValue) to ExpandoObject.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IDictionary">DevCase.Core.Extensions.IDictionary</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static ExpandoObject ToExpandoObject(
	this IDictionary<string, Object> sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToExpandoObject ( 
	sender As IDictionary(Of String, Object)
) As ExpandoObject
```

**VB Usage**<br />
``` VB Usage
Dim sender As IDictionary(Of String, Object)
Dim returnValue As ExpandoObject

returnValue = sender.ToExpandoObject()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static ExpandoObject^ ToExpandoObject(
	IDictionary<String^, Object^>^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToExpandoObject : 
        sender : IDictionary<string, Object> -> ExpandoObject 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IDictionary(String, Object)<br />The source IDictionary(TKey, TValue).</dd></dl>

#### Return Value
Type: ExpandoObject<br />The resulting ExpandoObject.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IDictionary(String, Object). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IDictionary_IDictionaryExtensions">IDictionaryExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IDictionary">DevCase.Core.Extensions.IDictionary Namespace</a><br />