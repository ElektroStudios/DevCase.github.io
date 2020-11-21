# FormExtensions.SetVisualStyle Method 
 

Changes the color appearance of the source <a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form</a> using the specified style.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void SetVisualStyle(
	this Form f,
	VisualStyle style,
	bool childControls
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub SetVisualStyle ( 
	f As Form,
	style As VisualStyle,
	childControls As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim f As Form
Dim style As VisualStyle
Dim childControls As Boolean

f.SetVisualStyle(style, childControls)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void SetVisualStyle(
	Form^ f, 
	VisualStyle style, 
	bool childControls
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SetVisualStyle : 
        f : Form * 
        style : VisualStyle * 
        childControls : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>f</dt><dd>Type: System.Windows.Forms.Form<br />The source Form.</dd><dt>style</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_VisualStyle">DevCase.Core.Application.UserInterface.VisualStyle</a><br />The visual style.</dd><dt>childControls</dt><dd>Type: System.Boolean<br />`true` (`True` in Visual Basic) to change the color appearance of child controls too.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Form. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Form_FormExtensions">FormExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form Namespace</a><br />