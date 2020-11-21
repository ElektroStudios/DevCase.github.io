# FormExtensions.ForEachControl(*T*) Method (Form, Boolean, Action(Control))
 

Iterate through all the controls of the specified type in the source Form and performs the specified action on each one.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void ForEachControl<T>(
	this Form f,
	bool recursive,
	Action<Control> action
)
where T : Control

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub ForEachControl(Of T As Control) ( 
	f As Form,
	recursive As Boolean,
	action As Action(Of Control)
)
```

**VB Usage**<br />
``` VB Usage
Dim f As Form
Dim recursive As Boolean
Dim action As Action(Of Control)

f.ForEachControl(recursive, action)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
where T : Control
static void ForEachControl(
	Form^ f, 
	bool recursive, 
	Action<Control^>^ action
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ForEachControl : 
        f : Form * 
        recursive : bool * 
        action : Action<Control> -> unit  when 'T : Control

```


#### Parameters
&nbsp;<dl><dt>f</dt><dd>Type: System.Windows.Forms.Form<br />The source Form.</dd><dt>recursive</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), iterates through controls of child controls too.</dd><dt>action</dt><dd>Type: System.Action(Control)<br />An Action(T) to perform on each control.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the control.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Form. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Form_FormExtensions">FormExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Form_FormExtensions_ForEachControl">ForEachControl Overload</a><br /><a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form Namespace</a><br />