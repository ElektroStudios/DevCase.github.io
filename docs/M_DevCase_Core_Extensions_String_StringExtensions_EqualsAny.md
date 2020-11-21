# StringExtensions.EqualsAny Method (String, IEnumerable(String))
 

Determines whether the specified string equals to any of the specified strings.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool EqualsAny(
	this string sender,
	IEnumerable<string> values
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function EqualsAny ( 
	sender As String,
	values As IEnumerable(Of String)
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim values As IEnumerable(Of String)
Dim returnValue As Boolean

returnValue = sender.EqualsAny(values)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool EqualsAny(
	String^ sender, 
	IEnumerable<String^>^ values
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member EqualsAny : 
        sender : string * 
        values : IEnumerable<string> -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>values</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />A collection of strings to match.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified string equal to any of the specified strings; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>values</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isEquals As Boolean = "Hello World!".EqualsAny({"Hello World!", "Hello!"}, StringComparison.OrdinalIgnoreCase)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_String_StringExtensions_EqualsAny">EqualsAny Overload</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />