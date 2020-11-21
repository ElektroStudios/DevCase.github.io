# StringExtensions.OccurrencesOf Method (String, String, StringComparison)
 

Counts the occurences of the specified string in the source String.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int OccurrencesOf(
	this string sender,
	string value,
	StringComparison stringComparison
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function OccurrencesOf ( 
	sender As String,
	value As String,
	stringComparison As StringComparison
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim value As String
Dim stringComparison As StringComparison
Dim returnValue As Integer

returnValue = sender.OccurrencesOf(value, 
	stringComparison)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static int OccurrencesOf(
	String^ sender, 
	String^ value, 
	StringComparison stringComparison
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member OccurrencesOf : 
        sender : string * 
        value : string * 
        stringComparison : StringComparison -> int 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>value</dt><dd>Type: System.String<br />The string to find.</dd><dt>stringComparison</dt><dd>Type: System.StringComparison<br />The string-case rules to compare.</dd></dl>

#### Return Value
Type: Int32<br />The amount of occurences of the specified string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
MsgBox("Hello world!".OccurrencesOf("ll", StringComparison.Ordinal))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_String_StringExtensions_OccurrencesOf">OccurrencesOf Overload</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />