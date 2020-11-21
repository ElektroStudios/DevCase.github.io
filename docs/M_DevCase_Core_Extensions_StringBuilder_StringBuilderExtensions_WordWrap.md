# StringBuilderExtensions.WordWrap Method 
 

Wraps words of the source StringBuilder to the beginning of the next line when necessary to fit the specified pixel width.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_StringBuilder">DevCase.Core.Extensions.StringBuilder</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static StringBuilder WordWrap(
	this StringBuilder sender,
	int maxWidth,
	Font font
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function WordWrap ( 
	sender As StringBuilder,
	maxWidth As Integer,
	font As Font
) As StringBuilder
```

**VB Usage**<br />
``` VB Usage
Dim sender As StringBuilder
Dim maxWidth As Integer
Dim font As Font
Dim returnValue As StringBuilder

returnValue = sender.WordWrap(maxWidth, 
	font)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static StringBuilder^ WordWrap(
	StringBuilder^ sender, 
	int maxWidth, 
	Font^ font
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member WordWrap : 
        sender : StringBuilder * 
        maxWidth : int * 
        font : Font -> StringBuilder 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Text.StringBuilder<br />The source StringBuilder.</dd><dt>maxWidth</dt><dd>Type: System.Int32<br />The maximum width, in pixels.</dd><dt>font</dt><dd>Type: System.Drawing.Font<br />The text font.</dd></dl>

#### Return Value
Type: StringBuilder<br />The resulting string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type StringBuilder. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Remarks
Credits to @undejavue solution: <a href="https://stackoverflow.com/a/36803501/1248295" target="_blank">https://stackoverflow.com/a/36803501/1248295</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim tb As New TextBox With {
    .Multiline = True,
    .ScrollBars = ScrollBars.Both,
    .WordWrap = False,
    .Size = New Drawing.Size(width:=250, height:=200)
}

Dim text As New StringBuilder
text.Append("Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.")
Dim wordWrappedText As StringBuilder = text.WordWrap(tb.Width, tb.Font)

Me.Controls.Add(tb)
tb.Text = wordWrappedText.ToString()

Console.WriteLine(wordWrappedText.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_StringBuilder_StringBuilderExtensions">StringBuilderExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_StringBuilder">DevCase.Core.Extensions.StringBuilder Namespace</a><br />