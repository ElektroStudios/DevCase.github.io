# StringExtensions.EndsWithAny Method (String, IEnumerable(String), StringComparison)
 

Determines whether the end of the specified string matches any of the specified strings.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool EndsWithAny(
	this string sender,
	IEnumerable<string> values,
	StringComparison comparisonType
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function EndsWithAny ( 
	sender As String,
	values As IEnumerable(Of String),
	comparisonType As StringComparison
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim values As IEnumerable(Of String)
Dim comparisonType As StringComparison
Dim returnValue As Boolean

returnValue = sender.EndsWithAny(values, 
	comparisonType)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool EndsWithAny(
	String^ sender, 
	IEnumerable<String^>^ values, 
	StringComparison comparisonType
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member EndsWithAny : 
        sender : string * 
        values : IEnumerable<string> * 
        comparisonType : StringComparison -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>values</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />A collection of strings to match.</dd><dt>comparisonType</dt><dd>Type: System.StringComparison<br />One of the enumeration values that determines how this string and value are compared.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the end of the specified string matches any of the specified strings; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>values</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isMatch As Boolean = "Hello World!".EndsWithAny({"hello", "world"}, StringComparison.OrdinalIgnoreCase)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_String_StringExtensions_EndsWithAny">EndsWithAny Overload</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />