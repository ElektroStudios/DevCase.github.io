# ColorExtensions.ToGrayScale Method 
 

Converts the specified Color to its grayscale color.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Color">DevCase.Core.Extensions.Color</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Color ToGrayScale(
	this Color color
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToGrayScale ( 
	color As Color
) As Color
```

**VB Usage**<br />
``` VB Usage
Dim color As Color
Dim returnValue As Color

returnValue = color.ToGrayScale()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Color ToGrayScale(
	Color color
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToGrayScale : 
        color : Color -> Color 

```


#### Parameters
&nbsp;<dl><dt>color</dt><dd>Type: System.Drawing.Color<br />\[Missing <param name="color"/> documentation for "M:DevCase.Core.Extensions.Color.ColorExtensions.ToGrayScale(System.Drawing.Color)"\]</dd></dl>

#### Return Value
Type: Color<br />The resulting grayscale color.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Color. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Color_ColorExtensions">ColorExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Color">DevCase.Core.Extensions.Color Namespace</a><br />