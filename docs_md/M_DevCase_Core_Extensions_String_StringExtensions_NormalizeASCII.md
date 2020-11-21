# StringExtensions.NormalizeASCII Method 
 

Normalizes the non-representable characters of the specified ASCII string.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string NormalizeASCII(
	this string sender,
	char normalizationChar = '.'
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function NormalizeASCII ( 
	sender As String,
	Optional normalizationChar As Char = "."C
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim normalizationChar As Char
Dim returnValue As String

returnValue = sender.NormalizeASCII(normalizationChar)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ NormalizeASCII(
	String^ sender, 
	wchar_t normalizationChar = L'.'
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member NormalizeASCII : 
        sender : string * 
        ?normalizationChar : char 
(* Defaults:
        let _normalizationChar = defaultArg normalizationChar '.'
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source string.</dd><dt>normalizationChar (Optional)</dt><dd>Type: System.Char<br />The character that must be used to replace non-representable chars. 

 Default character is: `"."c`</dd></dl>

#### Return Value
Type: String<br />The formated string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim data As Byte() = {26, 69, 223, 163}
Dim str As String = Encoding.ASCII.GetString(data)
MessageBox.Show(str.NormalizeASCII(normalizationChar:="."c))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />