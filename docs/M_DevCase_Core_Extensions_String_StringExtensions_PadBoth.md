# StringExtensions.PadBoth Method 
 

Returns a new string that center-aligns the characters in the source string by padding them on the left and the right with a specified Unicode character, for a specified total length.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string PadBoth(
	this string sender,
	int width,
	char paddingChar
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function PadBoth ( 
	sender As String,
	width As Integer,
	paddingChar As Char
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim width As Integer
Dim paddingChar As Char
Dim returnValue As String

returnValue = sender.PadBoth(width, 
	paddingChar)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ PadBoth(
	String^ sender, 
	int width, 
	wchar_t paddingChar
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member PadBoth : 
        sender : string * 
        width : int * 
        paddingChar : char -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>width</dt><dd>Type: System.Int32<br />The number of characters in the resulting string, equal to the number of original characters plus any additional padding characters.</dd><dt>paddingChar</dt><dd>Type: System.Char<br />A Unicode padding character.</dd></dl>

#### Return Value
Type: String<br />The resulting String.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "1234".PadBoth(8, "x"c)

MessageBox.Show(str)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />