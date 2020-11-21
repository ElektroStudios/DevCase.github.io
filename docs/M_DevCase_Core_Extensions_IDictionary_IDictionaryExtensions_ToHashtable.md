# IDictionaryExtensions.ToHashtable Method 
 

Converts an IDictionary to Hashtable.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IDictionary">DevCase.Core.Extensions.IDictionary</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Hashtable ToHashtable(
	this IDictionary sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToHashtable ( 
	sender As IDictionary
) As Hashtable
```

**VB Usage**<br />
``` VB Usage
Dim sender As IDictionary
Dim returnValue As Hashtable

returnValue = sender.ToHashtable()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Hashtable^ ToHashtable(
	IDictionary^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToHashtable : 
        sender : IDictionary -> Hashtable 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.IDictionary<br />The source IDictionary.</dd></dl>

#### Return Value
Type: Hashtable<br />The resulting Hashtable.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IDictionary. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IDictionary_IDictionaryExtensions">IDictionaryExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IDictionary">DevCase.Core.Extensions.IDictionary Namespace</a><br />