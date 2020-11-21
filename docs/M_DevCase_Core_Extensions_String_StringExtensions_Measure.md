# StringExtensions.Measure Method 
 

Provides the <a href="N_DevCase_Core_Extensions_Size">DevCase.Core.Extensions.Size</a>, in pixels, of the specified text when drawn with the specified font.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Size Measure(
	this string sender,
	Font font
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Measure ( 
	sender As String,
	font As Font
) As Size
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim font As Font
Dim returnValue As Size

returnValue = sender.Measure(font)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Size Measure(
	String^ sender, 
	Font^ font
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Measure : 
        sender : string * 
        font : Font -> Size 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>font</dt><dd>Type: System.Drawing.Font<br />\[Missing <param name="font"/> documentation for "M:DevCase.Core.Extensions.String.StringExtensions.Measure(System.String,System.Drawing.Font)"\]</dd></dl>

#### Return Value
Type: Size<br />The <a href="N_DevCase_Core_Extensions_Size">DevCase.Core.Extensions.Size</a>, in pixels, of the specified text when drawn with the specified font.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pxSize As Size = "Hello World!".Measure(New Font("Lucida Console", 12))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />