# StringBuilderExtensions.AppendFormatLine Method (StringBuilder, IFormatProvider, String, Object[])
 

Appends the string returned by processing a composite format string, which contains zero or more format items, to this instance. 

 Each format item is replaced by the string representation of a corresponding argument in a parameter array using a specified format provider. 

 Finally, appends the default line terminator to the end of the StringBuilder object.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_StringBuilder">DevCase.Core.Extensions.StringBuilder</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static StringBuilder AppendFormatLine(
	this StringBuilder sender,
	IFormatProvider provider,
	string format,
	params Object[] args
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function AppendFormatLine ( 
	sender As StringBuilder,
	provider As IFormatProvider,
	format As String,
	ParamArray args As Object()
) As StringBuilder
```

**VB Usage**<br />
``` VB Usage
Dim sender As StringBuilder
Dim provider As IFormatProvider
Dim format As String
Dim args As Object()
Dim returnValue As StringBuilder

returnValue = sender.AppendFormatLine(provider, 
	format, args)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static StringBuilder^ AppendFormatLine(
	StringBuilder^ sender, 
	IFormatProvider^ provider, 
	String^ format, 
	... array<Object^>^ args
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AppendFormatLine : 
        sender : StringBuilder * 
        provider : IFormatProvider * 
        format : string * 
        args : Object[] -> StringBuilder 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Text.StringBuilder<br />The source character.</dd><dt>provider</dt><dd>Type: System.IFormatProvider<br />An object that supplies culture-specific formatting information.</dd><dt>format</dt><dd>Type: System.String<br />A composite format string.</dd><dt>args</dt><dd>Type: System.Object[]<br />An array of objects to format.</dd></dl>

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
sb.AppendFormatLine(CultureInfo.CurrentCulture, "{0} {1} {2} {3}", "arg1", "arg2", "arg3", "etc...")

MessageBox.Show(sb.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_StringBuilder_StringBuilderExtensions">StringBuilderExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_StringBuilder_StringBuilderExtensions_AppendFormatLine">AppendFormatLine Overload</a><br /><a href="N_DevCase_Core_Extensions_StringBuilder">DevCase.Core.Extensions.StringBuilder Namespace</a><br />