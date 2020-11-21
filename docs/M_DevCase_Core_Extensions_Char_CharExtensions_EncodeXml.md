# CharExtensions.EncodeXml Method 
 

Encodes a character to its equivalent XML character code.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Char">DevCase.Core.Extensions.Char</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string EncodeXml(
	this char sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function EncodeXml ( 
	sender As Char
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As Char
Dim returnValue As String

returnValue = sender.EncodeXml()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ EncodeXml(
	wchar_t sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member EncodeXml : 
        sender : char -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Char<br />The source Char.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Char. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As Char = "'"c
Dim encoded As String = str.EncodeXml()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Char_CharExtensions">CharExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Char">DevCase.Core.Extensions.Char Namespace</a><br />