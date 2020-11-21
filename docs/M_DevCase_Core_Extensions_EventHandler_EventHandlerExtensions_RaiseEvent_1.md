# EventHandlerExtensions.RaiseEvent Method (EventHandler, Object, EventArgs)
 

Raises the event of the source EventHandler.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_EventHandler">DevCase.Core.Extensions.EventHandler</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void RaiseEvent(
	this EventHandler handler,
	Object sender,
	EventArgs e
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub RaiseEvent ( 
	handler As EventHandler,
	sender As Object,
	e As EventArgs
)
```

**VB Usage**<br />
``` VB Usage
Dim handler As EventHandler
Dim sender As Object
Dim e As EventArgs

handler.RaiseEvent(sender, e)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void RaiseEvent(
	EventHandler^ handler, 
	Object^ sender, 
	EventArgs^ e
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member RaiseEvent : 
        handler : EventHandler * 
        sender : Object * 
        e : EventArgs -> unit 

```


#### Parameters
&nbsp;<dl><dt>handler</dt><dd>Type: System.EventHandler<br />The source EventHandler.</dd><dt>sender</dt><dd>Type: System.Object<br />The source of the event.</dd><dt>e</dt><dd>Type: System.EventArgs<br />The event information.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type EventHandler. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim handler As New EventHandler(Of EventArgs)(AddressOf DoClick)
handler.RaiseEvent(Me, New EventArgs)

Private Sub DoClick(sender As Object, e As EventArgs) Handles MyBase.Click
    MsgBox("Click event raised.")
End Sub
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_EventHandler_EventHandlerExtensions">EventHandlerExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_EventHandler_EventHandlerExtensions_RaiseEvent">RaiseEvent Overload</a><br /><a href="N_DevCase_Core_Extensions_EventHandler">DevCase.Core.Extensions.EventHandler Namespace</a><br />