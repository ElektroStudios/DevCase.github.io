# StringExtensions.Replace Method 
 

Returns a new string in which all occurrences of the specified strings in the current instance are replaced with another specified using the specified string comparison type.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string Replace(
	this string sender,
	string findWhat,
	string replaceWith,
	StringComparison comparisonType
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Replace ( 
	sender As String,
	findWhat As String,
	replaceWith As String,
	comparisonType As StringComparison
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim findWhat As String
Dim replaceWith As String
Dim comparisonType As StringComparison
Dim returnValue As String

returnValue = sender.Replace(findWhat, 
	replaceWith, comparisonType)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ Replace(
	String^ sender, 
	String^ findWhat, 
	String^ replaceWith, 
	StringComparison comparisonType
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Replace : 
        sender : string * 
        findWhat : string * 
        replaceWith : string * 
        comparisonType : StringComparison -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>findWhat</dt><dd>Type: System.String<br />The string to match.</dd><dt>replaceWith</dt><dd>Type: System.String<br />\[Missing <param name="replaceWith"/> documentation for "M:DevCase.Core.Extensions.String.StringExtensions.Replace(System.String,System.String,System.String,System.StringComparison)"\]</dd><dt>comparisonType</dt><dd>Type: System.StringComparison<br />One of the enumeration values that specifies how the strings will be compared.</dd></dl>

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
Dim str As String = "Hello World!".Replace("world", "kitty", StringComparison.OrdinalIgnoreCase)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />