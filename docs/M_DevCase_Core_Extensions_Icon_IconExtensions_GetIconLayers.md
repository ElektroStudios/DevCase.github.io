# IconExtensions.GetIconLayers Method 
 

Gets all the icon layers contained in a Icon.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Icon">DevCase.Core.Extensions.Icon</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Icon[] GetIconLayers(
	this Icon sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetIconLayers ( 
	sender As Icon
) As Icon()
```

**VB Usage**<br />
``` VB Usage
Dim sender As Icon
Dim returnValue As Icon()

returnValue = sender.GetIconLayers()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static array<Icon^>^ GetIconLayers(
	Icon^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetIconLayers : 
        sender : Icon -> Icon[] 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Icon<br />The source Icon.</dd></dl>

#### Return Value
Type: Icon[]<br />An array of Icon containing the icon layers.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Icon. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ico As New Icon("C:\Image.ico")
Dim icons As Icon() = ico.GetIconLayers()

PictureBox1.BackgroundImageLayout = ImageLayout.None
PictureBox1.Image = Bitmap.FromHicon(icons(0).Handle)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Icon_IconExtensions">IconExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Icon">DevCase.Core.Extensions.Icon Namespace</a><br />