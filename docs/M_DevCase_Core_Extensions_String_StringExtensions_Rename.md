# StringExtensions.Rename Method 
 

Renames a string to the specified StringCase.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string Rename(
	this string sender,
	StringCase stringCase
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Rename ( 
	sender As String,
	stringCase As StringCase
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim stringCase As StringCase
Dim returnValue As String

returnValue = sender.Rename(stringCase)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ Rename(
	String^ sender, 
	StringCase stringCase
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Rename : 
        sender : string * 
        stringCase : StringCase -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>stringCase</dt><dd>Type: <a href="T_DevCase_Core_Text_StringCase">DevCase.Core.Text.StringCase</a><br />The <a href="T_DevCase_Core_Text_StringCase">StringCase</a>.</dd></dl>

#### Return Value
Type: String<br />The renamed string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "Hello World".Rename(StringCase.UpperCase)

MessageBox.Show(str)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />