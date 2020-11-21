# StringExtensions.EnsureEquals Method (String, String, StringComparison)
 

Determines whether the source string equals to the specified string. 

 If does not, it replaces the source string for the specified string.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string EnsureEquals(
	this string sender,
	string value,
	StringComparison comparisonType
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function EnsureEquals ( 
	sender As String,
	value As String,
	comparisonType As StringComparison
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim value As String
Dim comparisonType As StringComparison
Dim returnValue As String

returnValue = sender.EnsureEquals(value, 
	comparisonType)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ EnsureEquals(
	String^ sender, 
	String^ value, 
	StringComparison comparisonType
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member EnsureEquals : 
        sender : string * 
        value : string * 
        comparisonType : StringComparison -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>value</dt><dd>Type: System.String<br />The string to match.</dd><dt>comparisonType</dt><dd>Type: System.StringComparison<br />One of the enumeration values that determines how this string and value are compared.</dd></dl>

#### Return Value
Type: String<br />`true` (`True` in Visual Basic) if the source string equals to the specified string; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>value</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "Hello".EnsureEquals("H3ll0", StringComparison.OrdinalIgnoreCase)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_String_StringExtensions_EnsureEquals">EnsureEquals Overload</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />