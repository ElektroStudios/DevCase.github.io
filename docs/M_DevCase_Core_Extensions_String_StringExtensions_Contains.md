# StringExtensions.Contains Method 
 

Returns a value indicating whether the specified string occurs within this string.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool Contains(
	this string sender,
	string value,
	StringComparison comparisonType
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Contains ( 
	sender As String,
	value As String,
	comparisonType As StringComparison
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim value As String
Dim comparisonType As StringComparison
Dim returnValue As Boolean

returnValue = sender.Contains(value, 
	comparisonType)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool Contains(
	String^ sender, 
	String^ value, 
	StringComparison comparisonType
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Contains : 
        sender : string * 
        value : string * 
        comparisonType : StringComparison -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>value</dt><dd>Type: System.String<br />The String to find.</dd><dt>comparisonType</dt><dd>Type: System.StringComparison<br />One of the enumeration values that determines how this string and value are compared.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified string occurs within this string; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As Boolean = "Hello World".Contains("WORLD", StringComparison.OrdinalIgnoreCase)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />