# StringBuilderExtensions.AppendFormatLine Method (StringBuilder, String, Object, Object, Object)
 

Appends the string returned by processing a composite format string, which contains zero or more format items, to this instance. 

 Each format item is replaced by the string representation of either of three arguments. 

 Finally, appends the default line terminator to the end of the StringBuilder object.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_StringBuilder">DevCase.Core.Extensions.StringBuilder</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static StringBuilder AppendFormatLine(
	this StringBuilder sender,
	string format,
	Object arg0,
	Object arg1,
	Object arg2
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function AppendFormatLine ( 
	sender As StringBuilder,
	format As String,
	arg0 As Object,
	arg1 As Object,
	arg2 As Object
) As StringBuilder
```

**VB Usage**<br />
``` VB Usage
Dim sender As StringBuilder
Dim format As String
Dim arg0 As Object
Dim arg1 As Object
Dim arg2 As Object
Dim returnValue As StringBuilder

returnValue = sender.AppendFormatLine(format, 
	arg0, arg1, arg2)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static StringBuilder^ AppendFormatLine(
	StringBuilder^ sender, 
	String^ format, 
	Object^ arg0, 
	Object^ arg1, 
	Object^ arg2
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AppendFormatLine : 
        sender : StringBuilder * 
        format : string * 
        arg0 : Object * 
        arg1 : Object * 
        arg2 : Object -> StringBuilder 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Text.StringBuilder<br />The source character.</dd><dt>format</dt><dd>Type: System.String<br />A composite format string.</dd><dt>arg0</dt><dd>Type: System.Object<br />The first object to format.</dd><dt>arg1</dt><dd>Type: System.Object<br />The second object to format.</dd><dt>arg2</dt><dd>Type: System.Object<br />The third object to format.</dd></dl>

#### Return Value
Type: StringBuilder<br />A reference to this instance with format appended. 

 Each format item in format is replaced by the string representation of the corresponding object argument.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type StringBuilder. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim sb As New Global.System.Text.StringBuilder
sb.AppendFormatLine("{0} {1} {2}", "arg0", "arg1", "arg2")

MessageBox.Show(sb.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_StringBuilder_StringBuilderExtensions">StringBuilderExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_StringBuilder_StringBuilderExtensions_AppendFormatLine">AppendFormatLine Overload</a><br /><a href="N_DevCase_Core_Extensions_StringBuilder">DevCase.Core.Extensions.StringBuilder Namespace</a><br />