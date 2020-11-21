# ControlExtensions.InvokeWhenHandleValid Method 
 

Performs an action on the specified Control after its handle has been created (that is, when HandleCreated event is fired). 

 If the handle has already been created, the action is executed immediately.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Control">DevCase.Core.Extensions.Control</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void InvokeWhenHandleValid(
	this Control ctrl,
	Action<Control> action
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Sub InvokeWhenHandleValid ( 
	ctrl As Control,
	action As Action(Of Control)
)
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As Control
Dim action As Action(Of Control)

ctrl.InvokeWhenHandleValid(action)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static void InvokeWhenHandleValid(
	Control^ ctrl, 
	Action<Control^>^ action
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member InvokeWhenHandleValid : 
        ctrl : Control * 
        action : Action<Control> -> unit 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The source Control.</dd><dt>action</dt><dd>Type: System.Action(Control)<br />The action to perform on the source Control.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Control. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Control">DevCase.Core.Extensions.Control Namespace</a><br />