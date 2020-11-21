# FormExtensions.GetVerticalBorderSize Method 
 

Gets the size of the vertical border (the border of the left or right edge) of the source Form.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Size GetVerticalBorderSize(
	this Form f
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetVerticalBorderSize ( 
	f As Form
) As Size
```

**VB Usage**<br />
``` VB Usage
Dim f As Form
Dim returnValue As Size

returnValue = f.GetVerticalBorderSize()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Size GetVerticalBorderSize(
	Form^ f
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetVerticalBorderSize : 
        f : Form -> Size 

```


#### Parameters
&nbsp;<dl><dt>f</dt><dd>Type: System.Windows.Forms.Form<br />The source Form.</dd></dl>

#### Return Value
Type: Size<br />The size of the vertical border (the border of the left or right edge) of the source Form.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Form. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim verticalBorderSize As Size = GetVerticalBorderSize(Me)
Console.WriteLine(String.Format("Vertical Border Width  = {0}", verticalBorderSize.Width))
Console.WriteLine(String.Format("Vertical Border Height = {0}", verticalBorderSize.Height))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Form_FormExtensions">FormExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form Namespace</a><br />