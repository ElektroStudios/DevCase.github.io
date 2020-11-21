# ControlExtensions.GetBoundsRelativeToForm Method 
 

Gets the bounds of the source Control relatively to its parent Form.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Control">DevCase.Core.Extensions.Control</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Rectangle GetBoundsRelativeToForm(
	this Control sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetBoundsRelativeToForm ( 
	sender As Control
) As Rectangle
```

**VB Usage**<br />
``` VB Usage
Dim sender As Control
Dim returnValue As Rectangle

returnValue = sender.GetBoundsRelativeToForm()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Rectangle GetBoundsRelativeToForm(
	Control^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetBoundsRelativeToForm : 
        sender : Control -> Rectangle 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.Control<br />The source Control.</dd></dl>

#### Return Value
Type: Rectangle<br />The bounds of the source Control relatively to its parent Form.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Control. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ctrl As New Label
Dim rc As Rectangle = ctrl.GetBoundsRelativeToForm()
Console.WriteLine(rc.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Control">DevCase.Core.Extensions.Control Namespace</a><br />