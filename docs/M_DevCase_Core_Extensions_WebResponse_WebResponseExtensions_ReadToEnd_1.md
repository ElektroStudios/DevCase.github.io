# WebResponseExtensions.ReadToEnd Method (WebResponse, Encoding)
 

Reads the source WebResponse stream to the end.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_WebResponse">DevCase.Core.Extensions.WebResponse</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ReadToEnd(
	this WebResponse sender,
	Encoding enc
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ReadToEnd ( 
	sender As WebResponse,
	enc As Encoding
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As WebResponse
Dim enc As Encoding
Dim returnValue As String

returnValue = sender.ReadToEnd(enc)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ReadToEnd(
	WebResponse^ sender, 
	Encoding^ enc
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ReadToEnd : 
        sender : WebResponse * 
        enc : Encoding -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Net.WebResponse<br />The source WebResponse.</dd><dt>enc</dt><dd>Type: System.Text.Encoding<br />The source Encoding to use.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type WebResponse. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_WebResponse_WebResponseExtensions">WebResponseExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_WebResponse_WebResponseExtensions_ReadToEnd">ReadToEnd Overload</a><br /><a href="N_DevCase_Core_Extensions_WebResponse">DevCase.Core.Extensions.WebResponse Namespace</a><br />