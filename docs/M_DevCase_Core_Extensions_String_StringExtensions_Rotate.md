# StringExtensions.Rotate Method 
 

Rotates the position of the characters in a String.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string Rotate(
	this string sender,
	StringDirection direction,
	int positions
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Rotate ( 
	sender As String,
	direction As StringDirection,
	positions As Integer
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim direction As StringDirection
Dim positions As Integer
Dim returnValue As String

returnValue = sender.Rotate(direction, 
	positions)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ Rotate(
	String^ sender, 
	StringDirection direction, 
	int positions
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Rotate : 
        sender : string * 
        direction : StringDirection * 
        positions : int -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>direction</dt><dd>Type: <a href="T_DevCase_Core_Text_StringDirection">DevCase.Core.Text.StringDirection</a><br />A <a href="T_DevCase_Core_Text_StringDirection">StringDirection</a> that determines the rotation direction.</dd><dt>positions</dt><dd>Type: System.Int32<br />The amount of character positions to rotate.</dd></dl>

#### Return Value
Type: String<br />The rotated String.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>Value bigger than 0 is required.;positions</td></tr><tr><td>ArgumentOutOfRangeException</td><td>Value smaller than the source string length is required.;positions</td></tr><tr><td>InvalidEnumArgumentException</td><td>direction</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "Hello World".Rotate(StringDirection.Right, 1)

MessageBox.Show(str)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />