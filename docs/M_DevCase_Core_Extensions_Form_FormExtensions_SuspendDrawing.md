# FormExtensions.SuspendDrawing Method 
 

Prevents the source Form from being redrawn. 

 By calling this method, it will disallow painting events from firing on the source Form.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void SuspendDrawing(
	this Form sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub SuspendDrawing ( 
	sender As Form
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As Form

sender.SuspendDrawing()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void SuspendDrawing(
	Form^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SuspendDrawing : 
        sender : Form -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.Form<br />The source Form.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Form. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Form_FormExtensions">FormExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form Namespace</a><br />