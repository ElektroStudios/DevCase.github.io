# ControlExtensions.SendMouseButton Method (Control, MouseButton)
 

Sends a mouse button click to the specified control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Control">DevCase.Core.Extensions.Control</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool SendMouseButton(
	this Control ctrl,
	MouseButton button
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function SendMouseButton ( 
	ctrl As Control,
	button As MouseButton
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As Control
Dim button As MouseButton
Dim returnValue As Boolean

returnValue = ctrl.SendMouseButton(button)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static bool SendMouseButton(
	Control^ ctrl, 
	MouseButton button
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member SendMouseButton : 
        ctrl : Control * 
        button : MouseButton -> bool 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The source Control.</dd><dt>button</dt><dd>Type: <a href="T_DevCase_Core_IO_MouseButton">DevCase.Core.IO.MouseButton</a><br />The mouse button to simulate.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeds; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Control. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Control_ControlExtensions_SendMouseButton">SendMouseButton Overload</a><br /><a href="N_DevCase_Core_Extensions_Control">DevCase.Core.Extensions.Control Namespace</a><br />