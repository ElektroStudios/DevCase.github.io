# GraphicalUtil.ControlInvoke(*T*) Method 
 

Synchronouslly Executes an encapsulated method on the thread that owns the specified control. 

 This method avoids cross-threading exceptions.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ControlInvoke<T>(
	T ctrl,
	Action<T> method
)
where T : Control

```

**VB**<br />
``` VB
Public Shared Sub ControlInvoke(Of T As Control) ( 
	ctrl As T,
	method As Action(Of T)
)
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As T
Dim method As Action(Of T)

GraphicalUtil.ControlInvoke(ctrl, method)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : Control
static void ControlInvoke(
	T ctrl, 
	Action<T>^ method
)
```

**F#**<br />
``` F#
static member ControlInvoke : 
        ctrl : 'T * 
        method : Action<'T> -> unit  when 'T : Control

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: *T*<br />The Control to invoke.</dd><dt>method</dt><dd>Type: System.Action(*T*)<br />The encapsulated method to be called.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the control</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
ControlInvoke(TextBox1, Sub(tb) tb.Text = "Hello World!")

ControlInvoke(TextBox1, Sub(tb As TextBox)
                            For x As Integer = 0 To 50
                                tb.AppendText(CStr(x))
                            Next x
                        End Sub)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />