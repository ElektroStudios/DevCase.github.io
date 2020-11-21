# NameValueCollectionExtensions.ToDictionary Method 
 

Converts a NameValueCollection to Dictionary(TKey, TValue).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_NameValueCollection">DevCase.Core.Extensions.NameValueCollection</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Dictionary<string, string> ToDictionary(
	this NameValueCollection sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToDictionary ( 
	sender As NameValueCollection
) As Dictionary(Of String, String)
```

**VB Usage**<br />
``` VB Usage
Dim sender As NameValueCollection
Dim returnValue As Dictionary(Of String, String)

returnValue = sender.ToDictionary()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Dictionary<String^, String^>^ ToDictionary(
	NameValueCollection^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToDictionary : 
        sender : NameValueCollection -> Dictionary<string, string> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Specialized.NameValueCollection<br />The source NameValueCollection.</dd></dl>

#### Return Value
Type: Dictionary(String, String)<br />The resulting Dictionary(TKey, TValue).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type NameValueCollection. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_NameValueCollection_NameValueCollectionExtensions">NameValueCollectionExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_NameValueCollection">DevCase.Core.Extensions.NameValueCollection Namespace</a><br />