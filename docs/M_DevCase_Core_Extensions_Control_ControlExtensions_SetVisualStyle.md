# ControlExtensions.SetVisualStyle Method 
 

Changes the color appearance of the source Control using the specified style.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Control">DevCase.Core.Extensions.Control</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void SetVisualStyle(
	this Control ctrl,
	VisualStyle style
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub SetVisualStyle ( 
	ctrl As Control,
	style As VisualStyle
)
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As Control
Dim style As VisualStyle

ctrl.SetVisualStyle(style)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void SetVisualStyle(
	Control^ ctrl, 
	VisualStyle style
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SetVisualStyle : 
        ctrl : Control * 
        style : VisualStyle -> unit 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The source Control.</dd><dt>style</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_VisualStyle">DevCase.Core.Application.UserInterface.VisualStyle</a><br />The visual style.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Control. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Control">DevCase.Core.Extensions.Control Namespace</a><br />