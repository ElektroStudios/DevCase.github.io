# ControlExtensions.SetControlStyle Method 
 

Sets a specified ControlStyles flag to either `true` (`True` in Visual Basic) or `false` (`False` in Visual Basic) for the source control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Control">DevCase.Core.Extensions.Control</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void SetControlStyle(
	this Control sender,
	ControlStyles style,
	bool value
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub SetControlStyle ( 
	sender As Control,
	style As ControlStyles,
	value As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As Control
Dim style As ControlStyles
Dim value As Boolean

sender.SetControlStyle(style, value)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void SetControlStyle(
	Control^ sender, 
	ControlStyles style, 
	bool value
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SetControlStyle : 
        sender : Control * 
        style : ControlStyles * 
        value : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.Control<br />The source Control.</dd><dt>style</dt><dd>Type: System.Windows.Forms.ControlStyles<br />The ControlStyles bit to set.</dd><dt>value</dt><dd>Type: System.Boolean<br />`true` (`True` in Visual Basic) to apply the specified style to the control; otherwise, `false` (`False` in Visual Basic).</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Control. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Control">DevCase.Core.Extensions.Control Namespace</a><br />