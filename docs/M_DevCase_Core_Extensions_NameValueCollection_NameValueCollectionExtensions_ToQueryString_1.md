# NameValueCollectionExtensions.ToQueryString Method (NameValueCollection, String)
 

Converts the name and values of a NameValueCollection to a formatted web-request query string. 

 Consider this method to be the opposite of ParseQueryString(String).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_NameValueCollection">DevCase.Core.Extensions.NameValueCollection</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ToQueryString(
	this NameValueCollection sender,
	string baseAddress
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToQueryString ( 
	sender As NameValueCollection,
	baseAddress As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As NameValueCollection
Dim baseAddress As String
Dim returnValue As String

returnValue = sender.ToQueryString(baseAddress)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ToQueryString(
	NameValueCollection^ sender, 
	String^ baseAddress
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToQueryString : 
        sender : NameValueCollection * 
        baseAddress : string -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Specialized.NameValueCollection<br />The source NameValueCollection.</dd><dt>baseAddress</dt><dd>Type: System.String<br />The base url address.</dd></dl>

#### Return Value
Type: String<br />The resulting web-request query string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type NameValueCollection. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim params As New NameValueCollection()
params.Add("q", "Hello World")
params.Add("lr", "lang_en")
params.Add("ie", "utf-8")

Console.WriteLine(params.ToQueryString(baseAddress:="http://www.google.com/search"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_NameValueCollection_NameValueCollectionExtensions">NameValueCollectionExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_NameValueCollection_NameValueCollectionExtensions_ToQueryString">ToQueryString Overload</a><br /><a href="N_DevCase_Core_Extensions_NameValueCollection">DevCase.Core.Extensions.NameValueCollection Namespace</a><br />