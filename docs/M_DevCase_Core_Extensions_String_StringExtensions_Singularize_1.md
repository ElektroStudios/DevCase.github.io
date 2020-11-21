# StringExtensions.Singularize Method (String, CultureInfo)
 

Returns the singular form of the specified plural word, in the specified language.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string Singularize(
	this string plural,
	CultureInfo ci
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Singularize ( 
	plural As String,
	ci As CultureInfo
) As String
```

**VB Usage**<br />
``` VB Usage
Dim plural As String
Dim ci As CultureInfo
Dim returnValue As String

returnValue = plural.Singularize(ci)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ Singularize(
	String^ plural, 
	CultureInfo^ ci
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Singularize : 
        plural : string * 
        ci : CultureInfo -> string 

```


#### Parameters
&nbsp;<dl><dt>plural</dt><dd>Type: System.String<br />The plural word.</dd><dt>ci</dt><dd>Type: System.Globalization.CultureInfo<br />\[Missing <param name="ci"/> documentation for "M:DevCase.Core.Extensions.String.StringExtensions.Singularize(System.String,System.Globalization.CultureInfo)"\]</dd></dl>

#### Return Value
Type: String<br />The resulting word.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "I have tomatoes".Singularize(CultureInfo.GetCultureInfo("en-US"))

MessageBox.Show(str)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_String_StringExtensions_Singularize">Singularize Overload</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />