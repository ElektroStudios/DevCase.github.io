# FormExtensions.LockFormRegionToControls(*T*) Method (Form)
 

Locks the window region of the specified Form to the bounds of its child controls of the specified Type.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void LockFormRegionToControls<T>(
	this Form f
)
where T : Control

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub LockFormRegionToControls(Of T As Control) ( 
	f As Form
)
```

**VB Usage**<br />
``` VB Usage
Dim f As Form

f.LockFormRegionToControls()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
where T : Control
static void LockFormRegionToControls(
	Form^ f
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member LockFormRegionToControls : 
        f : Form -> unit  when 'T : Control

```


#### Parameters
&nbsp;<dl><dt>f</dt><dd>Type: System.Windows.Forms.Form<br />The source <a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form</a>.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The Type of control.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Form. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>NotImplementedException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
LockFormRegionToControls(Of Button)(Me)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Form_FormExtensions">FormExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Form_FormExtensions_LockFormRegionToControls">LockFormRegionToControls Overload</a><br /><a href="N_DevCase_Core_Extensions_Form">DevCase.Core.Extensions.Form Namespace</a><br />