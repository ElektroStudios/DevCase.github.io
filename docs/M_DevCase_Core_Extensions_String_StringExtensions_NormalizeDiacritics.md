# StringExtensions.NormalizeDiacritics Method 
 

Transforms the diacritic characters in a string, into standard fully compatible decomposited characters. 

 For example, having the diacritic "á" character, which its decomposited secuence is: "a" + "´", we return only "a".

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string NormalizeDiacritics(
	this string sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function NormalizeDiacritics ( 
	sender As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim returnValue As String

returnValue = sender.NormalizeDiacritics()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ NormalizeDiacritics(
	String^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member NormalizeDiacritics : 
        sender : string -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source string.</dd></dl>

#### Return Value
Type: String<br />The resulting normalized string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = ("áéíóú àèìòù äëïöü ñÑ çÇ").NormalizeDiacritics()
Console.WriteLine(str) ' Result: "aeiou aeiou aeiou nN cC"
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />