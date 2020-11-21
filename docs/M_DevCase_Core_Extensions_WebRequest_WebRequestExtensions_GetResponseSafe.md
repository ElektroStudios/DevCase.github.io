# WebRequestExtensions.GetResponseSafe Method 
 

Safely returns a response to an Internet request. 

 If an exception occurs trying to receive the response, it returns the response of the WebException.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_WebRequest">DevCase.Core.Extensions.WebRequest</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static WebResponse GetResponseSafe(
	this WebRequest sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetResponseSafe ( 
	sender As WebRequest
) As WebResponse
```

**VB Usage**<br />
``` VB Usage
Dim sender As WebRequest
Dim returnValue As WebResponse

returnValue = sender.GetResponseSafe()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static WebResponse^ GetResponseSafe(
	WebRequest^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetResponseSafe : 
        sender : WebRequest -> WebResponse 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Net.WebRequest<br />The source WebRequest.</dd></dl>

#### Return Value
Type: WebResponse<br />A WebResponse containing the response to the Internet request. 

 If an exception occurs trying to receive the response, it returns the response of the WebException.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type WebRequest. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_WebRequest_WebRequestExtensions">WebRequestExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_WebRequest">DevCase.Core.Extensions.WebRequest Namespace</a><br />