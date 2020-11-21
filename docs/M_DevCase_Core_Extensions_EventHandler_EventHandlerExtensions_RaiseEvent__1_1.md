# EventHandlerExtensions.RaiseEvent(*T*) Method (EventHandler(*T*), Object, *T*)
 

Raises the event of the source EventHandler.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_EventHandler">DevCase.Core.Extensions.EventHandler</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void RaiseEvent<T>(
	this EventHandler<T> handler,
	Object sender,
	T e
)
where T : EventArgs

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub RaiseEvent(Of T As EventArgs) ( 
	handler As EventHandler(Of T),
	sender As Object,
	e As T
)
```

**VB Usage**<br />
``` VB Usage
Dim handler As EventHandler(Of T)
Dim sender As Object
Dim e As T

handler.RaiseEvent(sender, e)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
where T : EventArgs
static void RaiseEvent(
	EventHandler<T>^ handler, 
	Object^ sender, 
	T e
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member RaiseEvent : 
        handler : EventHandler<'T> * 
        sender : Object * 
        e : 'T -> unit  when 'T : EventArgs

```


#### Parameters
&nbsp;<dl><dt>handler</dt><dd>Type: System.EventHandler(*T*)<br />The source EventHandler.</dd><dt>sender</dt><dd>Type: System.Object<br />The source of the event.</dd><dt>e</dt><dd>Type: *T*<br />The event information.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the event arguments.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type EventHandler(*T*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim handler As New EventHandler(Of FormClosingEventArgs)(AddressOf Me.Form1_FormClosing)
handler.RaiseEvent(Me, New FormClosingEventArgs(CloseReason.UserClosing, cancel:=True))

Private Sub Form1_FormClosing(sender As Object, e As FormClosingEventArgs) Handles MyBase.FormClosing
    MsgBox("FormClosing event raised.")
End Sub
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_EventHandler_EventHandlerExtensions">EventHandlerExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_EventHandler_EventHandlerExtensions_RaiseEvent">RaiseEvent Overload</a><br /><a href="N_DevCase_Core_Extensions_EventHandler">DevCase.Core.Extensions.EventHandler Namespace</a><br />