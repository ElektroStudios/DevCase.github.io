# FormExtensions.ResumeDrawing Method (Form, Boolean)
 

Allow the source Form to be redrawn. 

 By calling this method, it will allow painting events to be fired on the source Form.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void ResumeDrawing(
	this Form sender,
	bool redraw
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub ResumeDrawing ( 
	sender As Form,
	redraw As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As Form
Dim redraw As Boolean

sender.ResumeDrawing(redraw)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void ResumeDrawing(
	Form^ sender, 
	bool redraw
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ResumeDrawing : 
        sender : Form * 
        redraw : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.Form<br />The source Form.</dd><dt>redraw</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), causes the source Form to de redrawn (it has a similar effect as calling Refresh() method).</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Form. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Form_FormExtensions">FormExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Form_FormExtensions_ResumeDrawing">ResumeDrawing Overload</a><br /><a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form Namespace</a><br />