# StringExtensions.ReplaceAllRegex Method 
 

Returns a new string in which all occurrences of the specified strings in the current instance are replaced with another specified string using a regular expression.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ReplaceAllRegex(
	this string sender,
	IEnumerable<string> findWhat,
	string replaceWith,
	RegexOptions regexOptions
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ReplaceAllRegex ( 
	sender As String,
	findWhat As IEnumerable(Of String),
	replaceWith As String,
	regexOptions As RegexOptions
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim findWhat As IEnumerable(Of String)
Dim replaceWith As String
Dim regexOptions As RegexOptions
Dim returnValue As String

returnValue = sender.ReplaceAllRegex(findWhat, 
	replaceWith, regexOptions)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ReplaceAllRegex(
	String^ sender, 
	IEnumerable<String^>^ findWhat, 
	String^ replaceWith, 
	RegexOptions regexOptions
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ReplaceAllRegex : 
        sender : string * 
        findWhat : IEnumerable<string> * 
        replaceWith : string * 
        regexOptions : RegexOptions -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>findWhat</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />A collection of Regex expressions to match.</dd><dt>replaceWith</dt><dd>Type: System.String<br />\[Missing <param name="replaceWith"/> documentation for "M:DevCase.Core.Extensions.String.StringExtensions.ReplaceAllRegex(System.String,System.Collections.Generic.IEnumerable{System.String},System.String,System.Text.RegularExpressions.RegexOptions)"\]</dd><dt>regexOptions</dt><dd>Type: System.Text.RegularExpressions.RegexOptions<br />The RegexOptions.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>findWhat</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "Hello World!".ReplaceAllRegex({"\s", "\!"}, "_", RegexOptions.IgnoreCase)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />