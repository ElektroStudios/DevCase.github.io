# StringExtensions.Pluralize Method (String, CultureInfo)
 

Returns the plural form of the specified singular word, in the specified language.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string Pluralize(
	this string singular,
	CultureInfo ci
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Pluralize ( 
	singular As String,
	ci As CultureInfo
) As String
```

**VB Usage**<br />
``` VB Usage
Dim singular As String
Dim ci As CultureInfo
Dim returnValue As String

returnValue = singular.Pluralize(ci)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ Pluralize(
	String^ singular, 
	CultureInfo^ ci
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Pluralize : 
        singular : string * 
        ci : CultureInfo -> string 

```


#### Parameters
&nbsp;<dl><dt>singular</dt><dd>Type: System.String<br />The singular word.</dd><dt>ci</dt><dd>Type: System.Globalization.CultureInfo<br />\[Missing <param name="ci"/> documentation for "M:DevCase.Core.Extensions.String.StringExtensions.Pluralize(System.String,System.Globalization.CultureInfo)"\]</dd></dl>

#### Return Value
Type: String<br />The resulting word.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "I have tomato".Pluralize(CultureInfo.GetCultureInfo("en-US"))

MessageBox.Show(str)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_String_StringExtensions_Pluralize">Pluralize Overload</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />