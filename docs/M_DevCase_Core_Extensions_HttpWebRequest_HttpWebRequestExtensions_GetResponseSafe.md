# HttpWebRequestExtensions.GetResponseSafe Method 
 

Safely returns a response to an Internet request. 

 If an exception occurs trying to receive the response, it returns the response of the WebException.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_HttpWebRequest">DevCase.Core.Extensions.HttpWebRequest</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static WebResponse GetResponseSafe(
	this HttpWebRequest sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetResponseSafe ( 
	sender As HttpWebRequest
) As WebResponse
```

**VB Usage**<br />
``` VB Usage
Dim sender As HttpWebRequest
Dim returnValue As WebResponse

returnValue = sender.GetResponseSafe()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static WebResponse^ GetResponseSafe(
	HttpWebRequest^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetResponseSafe : 
        sender : HttpWebRequest -> WebResponse 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Net.HttpWebRequest<br />The source WebRequest.</dd></dl>

#### Return Value
Type: WebResponse<br />A WebResponse containing the response to the Internet request. 

 If an exception occurs trying to receive the response, it returns the response of the WebException.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type HttpWebRequest. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_HttpWebRequest_HttpWebRequestExtensions">HttpWebRequestExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_HttpWebRequest">DevCase.Core.Extensions.HttpWebRequest Namespace</a><br />