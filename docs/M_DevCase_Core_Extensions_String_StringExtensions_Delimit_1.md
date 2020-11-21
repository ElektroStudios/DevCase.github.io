# StringExtensions.Delimit Method (String, String, String, Int32, RegexOptions)
 

Delimits once a string by the given two delimiters.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string Delimit(
	this string sender,
	string delimiterA,
	string delimiterB,
	int count,
	RegexOptions options = RegexOptions.None
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Delimit ( 
	sender As String,
	delimiterA As String,
	delimiterB As String,
	count As Integer,
	Optional options As RegexOptions = RegexOptions.None
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim delimiterA As String
Dim delimiterB As String
Dim count As Integer
Dim options As RegexOptions
Dim returnValue As String

returnValue = sender.Delimit(delimiterA, 
	delimiterB, count, options)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ Delimit(
	String^ sender, 
	String^ delimiterA, 
	String^ delimiterB, 
	int count, 
	RegexOptions options = RegexOptions::None
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Delimit : 
        sender : string * 
        delimiterA : string * 
        delimiterB : string * 
        count : int * 
        ?options : RegexOptions 
(* Defaults:
        let _options = defaultArg options RegexOptions.None
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>delimiterA</dt><dd>Type: System.String<br />The first delimiter string.</dd><dt>delimiterB</dt><dd>Type: System.String<br />The last delimiter string.</dd><dt>count</dt><dd>Type: System.Int32<br />The *delimiterA* occurrence count.</dd><dt>options (Optional)</dt><dd>Type: System.Text.RegularExpressions.RegexOptions<br />The RegexOptions.</dd></dl>

#### Return Value
Type: String<br />The delimited string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
MessageBox.Show("You are welcome to my party tomorrow!".Delimit("o", "tomorrow", 1))
MessageBox.Show("You are welcome to my party tomorrow!".Delimit("o", "Y", 1, RegexOptions.RightToLeft))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_String_StringExtensions_Delimit">Delimit Overload</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />