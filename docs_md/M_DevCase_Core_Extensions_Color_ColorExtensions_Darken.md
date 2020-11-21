# ColorExtensions.Darken Method 
 

Darkens a Color by increasing its RGB values by the specified percentage.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Color">DevCase.Core.Extensions.Color</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Color Darken(
	this Color color,
	float percent
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function Darken ( 
	color As Color,
	percent As Single
) As Color
```

**VB Usage**<br />
``` VB Usage
Dim color As Color
Dim percent As Single
Dim returnValue As Color

returnValue = color.Darken(percent)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static Color Darken(
	Color color, 
	float percent
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member Darken : 
        color : Color * 
        percent : float32 -> Color 

```


#### Parameters
&nbsp;<dl><dt>color</dt><dd>Type: System.Drawing.Color<br />The source Color.</dd><dt>percent</dt><dd>Type: System.Single<br />The percentage by which to darken the source color. 

 If *percent* is `1.0F` (100%), the returned color will be Black.</dd></dl>

#### Return Value
Type: Color<br />A Color with its RGB values increased by the specified percentage.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Color. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Color_ColorExtensions">ColorExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Color">DevCase.Core.Extensions.Color Namespace</a><br />