# StringExtensions.LastIndexOfAnyRegEx Method (String, IEnumerable(String), Int32, RegexOptions)
 

Reports the zero-based index of the last occurrence in this instance of any Regex expression in a specified array.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int LastIndexOfAnyRegEx(
	this string sender,
	IEnumerable<string> findExpressions,
	int startIndex,
	RegexOptions regexOptions = RegexOptions.None
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function LastIndexOfAnyRegEx ( 
	sender As String,
	findExpressions As IEnumerable(Of String),
	startIndex As Integer,
	Optional regexOptions As RegexOptions = RegexOptions.None
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim findExpressions As IEnumerable(Of String)
Dim startIndex As Integer
Dim regexOptions As RegexOptions
Dim returnValue As Integer

returnValue = sender.LastIndexOfAnyRegEx(findExpressions, 
	startIndex, regexOptions)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static int LastIndexOfAnyRegEx(
	String^ sender, 
	IEnumerable<String^>^ findExpressions, 
	int startIndex, 
	RegexOptions regexOptions = RegexOptions::None
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member LastIndexOfAnyRegEx : 
        sender : string * 
        findExpressions : IEnumerable<string> * 
        startIndex : int * 
        ?regexOptions : RegexOptions 
(* Defaults:
        let _regexOptions = defaultArg regexOptions RegexOptions.None
*)
-> int 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>findExpressions</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />An IEnumerable(T) containing one or more Regex expression to find.</dd><dt>startIndex</dt><dd>Type: System.Int32<br />The search starting position.</dd><dt>regexOptions (Optional)</dt><dd>Type: System.Text.RegularExpressions.RegexOptions<br />The RegexOptions.</dd></dl>

#### Return Value
Type: Int32<br />The zero-based index position of the last occurrence in this instance where any regular expression in *findExpressions* was found; or -1 if no expression in *findExpressions* was found.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>findExpressions</td></tr><tr><td>ArgumentOutOfRangeException</td><td>startIndex</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim Dim lastIndexOfAny As Integer = 
    "Hello World!".LastIndexOfAnyRegEx({"\s", "o"c}, startIndex:=0, regexOptions:=RegexOptions.IgnoreCase)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_String_StringExtensions_LastIndexOfAnyRegEx">LastIndexOfAnyRegEx Overload</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />