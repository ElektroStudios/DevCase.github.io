# IntegerExtensions.Formatted Method (Int32, Int32, CultureInfo)
 

Formats a value by placing dots or commas in the corresponding positions depending on the specified culture.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Integer">DevCase.Core.Extensions.Integer</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string Formatted(
	this int sender,
	int precision,
	CultureInfo culture
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Formatted ( 
	sender As Integer,
	precision As Integer,
	culture As CultureInfo
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As Integer
Dim precision As Integer
Dim culture As CultureInfo
Dim returnValue As String

returnValue = sender.Formatted(precision, 
	culture)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ Formatted(
	int sender, 
	int precision, 
	CultureInfo^ culture
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Formatted : 
        sender : int * 
        precision : int * 
        culture : CultureInfo -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Int32<br />The source value.</dd><dt>precision</dt><dd>Type: System.Int32<br />The decimals precision.</dd><dt>culture</dt><dd>Type: System.Globalization.CultureInfo<br />The culture format.</dd></dl>

#### Return Value
Type: String<br />The formatted value.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Int32. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim number As String = 10000I.Formatted(precision:=0, culture:=CultureInfo.GetCultureInfo("en-US"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Integer_IntegerExtensions">IntegerExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Integer_IntegerExtensions_Formatted">Formatted Overload</a><br /><a href="N_DevCase_Core_Extensions_Integer">DevCase.Core.Extensions.Integer Namespace</a><br />