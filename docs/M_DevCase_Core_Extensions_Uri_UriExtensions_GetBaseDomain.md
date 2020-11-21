# UriExtensions.GetBaseDomain Method 
 

Returns the base domain from Host property. 

 Example: www.domain.com returns: domain.com

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Uri">DevCase.Core.Extensions.Uri</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string GetBaseDomain(
	this Uri uri
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetBaseDomain ( 
	uri As Uri
) As String
```

**VB Usage**<br />
``` VB Usage
Dim uri As Uri
Dim returnValue As String

returnValue = uri.GetBaseDomain()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ GetBaseDomain(
	Uri^ uri
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetBaseDomain : 
        uri : Uri -> string 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />The source Uri</dd></dl>

#### Return Value
Type: String<br />The base domain.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Uri. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Uri_UriExtensions">UriExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Uri">DevCase.Core.Extensions.Uri Namespace</a><br />