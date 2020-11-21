# BBCodeExtensions.ToHtml Method (IEnumerable(BBCodeNode), Boolean)
 

Converts a collection of <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a> to HTML

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_BBCode">DevCase.Core.Extensions.BBCode</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ToHtml(
	this IEnumerable<BBCodeNode> nodes,
	bool throwOnError
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function ToHtml ( 
	nodes As IEnumerable(Of BBCodeNode),
	throwOnError As Boolean
) As String
```

**VB Usage**<br />
``` VB Usage
Dim nodes As IEnumerable(Of BBCodeNode)
Dim throwOnError As Boolean
Dim returnValue As String

returnValue = nodes.ToHtml(throwOnError)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static String^ ToHtml(
	IEnumerable<BBCodeNode^>^ nodes, 
	bool throwOnError
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member ToHtml : 
        nodes : IEnumerable<BBCodeNode> * 
        throwOnError : bool -> string 

```


#### Parameters
&nbsp;<dl><dt>nodes</dt><dd>Type: System.Collections.Generic.IEnumerable(<a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a>)<br />\[Missing <param name="nodes"/> documentation for "M:DevCase.Core.Extensions.BBCode.BBCodeExtensions.ToHtml(System.Collections.Generic.IEnumerable{DevCase.Core.NET.BBCodeNode},System.Boolean)"\]</dd><dt>throwOnError</dt><dd>Type: System.Boolean<br />A value indicating whether to throw an exception when an error is encountered. 

 If `false` (`False` in Visual Basic), errors will be silently ignored.</dd></dl>

#### Return Value
Type: String<br />The HTML source as a string

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(<a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a>). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_BBCode_BBCodeExtensions">BBCodeExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_BBCode_BBCodeExtensions_ToHtml">ToHtml Overload</a><br /><a href="N_DevCase_Core_Extensions_BBCode">DevCase.Core.Extensions.BBCode Namespace</a><br />