# HttpResponseExtensions.Reload Method 
 

Reloads the source HttpResponse.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_HttpResponse">DevCase.Core.Extensions.HttpResponse</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void Reload(
	this HttpResponse sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub Reload ( 
	sender As HttpResponse
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As HttpResponse

sender.Reload()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void Reload(
	HttpResponse^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Reload : 
        sender : HttpResponse -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Web.HttpResponse<br />The source HttpResponse.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type HttpResponse. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_HttpResponse_HttpResponseExtensions">HttpResponseExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_HttpResponse">DevCase.Core.Extensions.HttpResponse Namespace</a><br />