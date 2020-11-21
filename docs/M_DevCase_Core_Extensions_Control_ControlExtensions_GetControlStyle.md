# ControlExtensions.GetControlStyle Method 
 

Gets the value of the specified ControlStyles bit for the source control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Control">DevCase.Core.Extensions.Control</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool GetControlStyle(
	this Control sender,
	ControlStyles styles
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetControlStyle ( 
	sender As Control,
	styles As ControlStyles
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As Control
Dim styles As ControlStyles
Dim returnValue As Boolean

returnValue = sender.GetControlStyle(styles)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool GetControlStyle(
	Control^ sender, 
	ControlStyles styles
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetControlStyle : 
        sender : Control * 
        styles : ControlStyles -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.Control<br />The source Control.</dd><dt>styles</dt><dd>Type: System.Windows.Forms.ControlStyles<br />The ControlStyles bit to return the value from.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified control style bit is set to `true` (`True` in Visual Basic); otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Control. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Control">DevCase.Core.Extensions.Control Namespace</a><br />