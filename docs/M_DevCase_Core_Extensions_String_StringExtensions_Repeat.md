# StringExtensions.Repeat Method 
 

Returns the source string repeated the specified amount of times.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string Repeat(
	this string sender,
	int count
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Repeat ( 
	sender As String,
	count As Integer
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim count As Integer
Dim returnValue As String

returnValue = sender.Repeat(count)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ Repeat(
	String^ sender, 
	int count
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Repeat : 
        sender : string * 
        count : int -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>count</dt><dd>Type: System.Int32<br />The amount of times to repeat.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>value</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "Hello World!".Repeat(2)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />