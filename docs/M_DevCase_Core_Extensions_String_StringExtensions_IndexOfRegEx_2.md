# StringExtensions.IndexOfRegEx Method (String, String, RegexOptions)
 

Reports the zero-based index of the first occurrence of the specified string in this instance, using a regular expression.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int IndexOfRegEx(
	this string sender,
	string findExpression,
	RegexOptions regexOptions = RegexOptions.None
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IndexOfRegEx ( 
	sender As String,
	findExpression As String,
	Optional regexOptions As RegexOptions = RegexOptions.None
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim findExpression As String
Dim regexOptions As RegexOptions
Dim returnValue As Integer

returnValue = sender.IndexOfRegEx(findExpression, 
	regexOptions)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static int IndexOfRegEx(
	String^ sender, 
	String^ findExpression, 
	RegexOptions regexOptions = RegexOptions::None
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IndexOfRegEx : 
        sender : string * 
        findExpression : string * 
        ?regexOptions : RegexOptions 
(* Defaults:
        let _regexOptions = defaultArg regexOptions RegexOptions.None
*)
-> int 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>findExpression</dt><dd>Type: System.String<br />The Regex find expression.</dd><dt>regexOptions (Optional)</dt><dd>Type: System.Text.RegularExpressions.RegexOptions<br />The RegexOptions.</dd></dl>

#### Return Value
Type: Int32<br />The zero-based index position of value if that string is found, or -1 if it is not.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>findExpression</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim indexOf As Integer = 
    "Hello World!".IndexOfRegEx("\sWorld", regexOptions:=RegexOptions.IgnoreCase)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_String_StringExtensions_IndexOfRegEx">IndexOfRegEx Overload</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />