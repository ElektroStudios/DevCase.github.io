# StringExtensions.IsCaseOf Method 
 

Determines wheter a String is written in the specified string case.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsCaseOf(
	this string sender,
	StringCase stringCase
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsCaseOf ( 
	sender As String,
	stringCase As StringCase
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim stringCase As StringCase
Dim returnValue As Boolean

returnValue = sender.IsCaseOf(stringCase)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsCaseOf(
	String^ sender, 
	StringCase stringCase
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsCaseOf : 
        sender : string * 
        stringCase : StringCase -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source string.</dd><dt>stringCase</dt><dd>Type: <a href="T_DevCase_Core_Text_StringCase">DevCase.Core.Text.StringCase</a><br />\[Missing <param name="stringCase"/> documentation for "M:DevCase.Core.Extensions.String.StringExtensions.IsCaseOf(System.String,DevCase.Core.Text.StringCase)"\]</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if String is written in the specified string case, `false` (`False` in Visual Basic) otherwise.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>sender</td></tr><tr><td>NotImplementedException</td><td>This function does not support the specified string case.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
MessageBox.Show("HELLO WORLD".IsCaseOf(StringCase.UpperCase))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />