# ControlExtensions.ForEachControl Method (Control, Boolean, Action(Control))
 

Iterate through all the controls in the source Control and performs the specified action on each one.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Control">DevCase.Core.Extensions.Control</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void ForEachControl(
	this Control parent,
	bool recursive,
	Action<Control> action
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub ForEachControl ( 
	parent As Control,
	recursive As Boolean,
	action As Action(Of Control)
)
```

**VB Usage**<br />
``` VB Usage
Dim parent As Control
Dim recursive As Boolean
Dim action As Action(Of Control)

parent.ForEachControl(recursive, 
	action)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void ForEachControl(
	Control^ parent, 
	bool recursive, 
	Action<Control^>^ action
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ForEachControl : 
        parent : Control * 
        recursive : bool * 
        action : Action<Control> -> unit 

```


#### Parameters
&nbsp;<dl><dt>parent</dt><dd>Type: System.Windows.Forms.Control<br />The source Control.</dd><dt>recursive</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), iterates through controls of child controls too.</dd><dt>action</dt><dd>Type: System.Action(Control)<br />An Action(T) to perform on each control.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Control. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Control_ControlExtensions_ForEachControl">ForEachControl Overload</a><br /><a href="N_DevCase_Core_Extensions_Control">DevCase.Core.Extensions.Control Namespace</a><br />