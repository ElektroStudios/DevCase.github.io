# UriExtensions.ToNameValueCollection Method (Uri)
 

Gets que query of the source Uri using UTF8.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Uri">DevCase.Core.Extensions.Uri</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static NameValueCollection ToNameValueCollection(
	this Uri sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToNameValueCollection ( 
	sender As Uri
) As NameValueCollection
```

**VB Usage**<br />
``` VB Usage
Dim sender As Uri
Dim returnValue As NameValueCollection

returnValue = sender.ToNameValueCollection()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static NameValueCollection^ ToNameValueCollection(
	Uri^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToNameValueCollection : 
        sender : Uri -> NameValueCollection 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Uri<br />The source Uri.</dd></dl>

#### Return Value
Type: NameValueCollection<br />The resulting NameValueCollection containing the query parameters and values.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Uri. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim uri As New Uri("https://www.youtube.com/watch?v=FtcVlSytJF4")
Dim query As NameValueCollection = ToNameValueCollection(uri)
Dim id As String = Query("v")
Console.WriteLine(id)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Uri_UriExtensions">UriExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Uri_UriExtensions_ToNameValueCollection">ToNameValueCollection Overload</a><br /><a href="N_DevCase_Core_Extensions_Uri">DevCase.Core.Extensions.Uri Namespace</a><br />