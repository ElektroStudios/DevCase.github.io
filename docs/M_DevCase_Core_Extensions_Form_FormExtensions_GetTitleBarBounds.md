# FormExtensions.GetTitleBarBounds Method 
 

Gets the titlebar bounds of the source Form.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Rectangle GetTitleBarBounds(
	this Form f,
	bool includeBorderSizes
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetTitleBarBounds ( 
	f As Form,
	includeBorderSizes As Boolean
) As Rectangle
```

**VB Usage**<br />
``` VB Usage
Dim f As Form
Dim includeBorderSizes As Boolean
Dim returnValue As Rectangle

returnValue = f.GetTitleBarBounds(includeBorderSizes)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Rectangle GetTitleBarBounds(
	Form^ f, 
	bool includeBorderSizes
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetTitleBarBounds : 
        f : Form * 
        includeBorderSizes : bool -> Rectangle 

```


#### Parameters
&nbsp;<dl><dt>f</dt><dd>Type: System.Windows.Forms.Form<br />The source Form.</dd><dt>includeBorderSizes</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), the titlebar bounds will include the bounds of the top, left and right border edges. 

 If `false` (`False` in Visual Basic), the titlebar bounds will NOT include the bounds of the top, left and right border edges.</dd></dl>

#### Return Value
Type: Rectangle<br />The titlebar bounds (including the border sizes) of the source Form.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Form. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim titleBarBoundsWithBorders As Rectangle = GetTitleBarBounds(Me, includeBorderSizes:=True)
Console.WriteLine(String.Format("TitleBar Bounds (including borders) Width  = {0}", titleBarBoundsWithBorders.Width))
Console.WriteLine(String.Format("TitleBar Bounds (including borders) Height = {0}", titleBarBoundsWithBorders.Height))
Console.WriteLine(String.Format("TitleBar Bounds (including borders) Pos. X = {0}", titleBarBoundsWithBorders.X))
Console.WriteLine(String.Format("TitleBar Bounds (including borders) Pos. Y = {0}", titleBarBoundsWithBorders.Y))

Dim titleBarBoundsWithoutBorders As Rectangle = GetTitleBarBounds(Me, includeBorderSizes:=False)
Console.WriteLine(String.Format("TitleBar Bounds (not including borders) Width  = {0}", titleBarBoundsWithoutBorders.Width))
Console.WriteLine(String.Format("TitleBar Bounds (not including borders) Height = {0}", titleBarBoundsWithoutBorders.Height))
Console.WriteLine(String.Format("TitleBar Bounds (not including borders) Pos. X = {0}", titleBarBoundsWithoutBorders.X))
Console.WriteLine(String.Format("TitleBar Bounds (not including borders) Pos. Y = {0}", titleBarBoundsWithoutBorders.Y))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Form_FormExtensions">FormExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form Namespace</a><br />