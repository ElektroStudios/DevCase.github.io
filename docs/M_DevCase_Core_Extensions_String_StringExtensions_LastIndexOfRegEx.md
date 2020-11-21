# StringExtensions.LastIndexOfRegEx Method (String, String, Int32, Int32, RegexOptions)
 

Reports the zero-based index position of the last occurrence of a specified string within this instance, using a regular expression.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int LastIndexOfRegEx(
	this string sender,
	string findExpression,
	int startIndex,
	int count,
	RegexOptions regexOptions = RegexOptions.None
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function LastIndexOfRegEx ( 
	sender As String,
	findExpression As String,
	startIndex As Integer,
	count As Integer,
	Optional regexOptions As RegexOptions = RegexOptions.None
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim findExpression As String
Dim startIndex As Integer
Dim count As Integer
Dim regexOptions As RegexOptions
Dim returnValue As Integer

returnValue = sender.LastIndexOfRegEx(findExpression, 
	startIndex, count, regexOptions)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static int LastIndexOfRegEx(
	String^ sender, 
	String^ findExpression, 
	int startIndex, 
	int count, 
	RegexOptions regexOptions = RegexOptions::None
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member LastIndexOfRegEx : 
        sender : string * 
        findExpression : string * 
        startIndex : int * 
        count : int * 
        ?regexOptions : RegexOptions 
(* Defaults:
        let _regexOptions = defaultArg regexOptions RegexOptions.None
*)
-> int 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>findExpression</dt><dd>Type: System.String<br />The Regex find expression.</dd><dt>startIndex</dt><dd>Type: System.Int32<br />The search starting position.</dd><dt>count</dt><dd>Type: System.Int32<br />The number of character positions to examine.</dd><dt>regexOptions (Optional)</dt><dd>Type: System.Text.RegularExpressions.RegexOptions<br />The RegexOptions.</dd></dl>

#### Return Value
Type: Int32<br />The zero-based index position of value if that string is found, or -1 if it is not found.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>findExpression</td></tr><tr><td>ArgumentOutOfRangeException</td><td>startIndex or count</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim lastIndexOf As Integer = 
    "Hello World!".LastIndexOfRegEx("\s", startIndex:=0, count:=6, regexOptions:=RegexOptions.IgnoreCase)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_String_StringExtensions_LastIndexOfRegEx">LastIndexOfRegEx Overload</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />