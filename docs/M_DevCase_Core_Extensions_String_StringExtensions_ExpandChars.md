# StringExtensions.ExpandChars Method (String, Char, Int32)
 

Expands the characters of a String by adding the specified separator char.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ExpandChars(
	this string sender,
	char separator,
	int count
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ExpandChars ( 
	sender As String,
	separator As Char,
	count As Integer
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim separator As Char
Dim count As Integer
Dim returnValue As String

returnValue = sender.ExpandChars(separator, 
	count)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ExpandChars(
	String^ sender, 
	wchar_t separator, 
	int count
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ExpandChars : 
        sender : string * 
        separator : char * 
        count : int -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source string.</dd><dt>separator</dt><dd>Type: System.Char<br />The character used to expand the characters.</dd><dt>count</dt><dd>Type: System.Int32<br />The amount of times to repeat the separator character.</dd></dl>

#### Return Value
Type: String<br />The expanded string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>Value bigger than 0 is required.;count</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
MessageBox.Show("Hello World".ExpandChars(" "c, 2))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_String_StringExtensions_ExpandChars">ExpandChars Overload</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />