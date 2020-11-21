# EventInfoExtensions.RemoveEventHandler Method 
 

Removes an event handler from an event source.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_EventInfo">DevCase.Core.Extensions.EventInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void RemoveEventHandler(
	this EventInfo eventInfo,
	Component target,
	string handlerName
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub RemoveEventHandler ( 
	eventInfo As EventInfo,
	target As Component,
	handlerName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim eventInfo As EventInfo
Dim target As Component
Dim handlerName As String

eventInfo.RemoveEventHandler(target, 
	handlerName)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void RemoveEventHandler(
	EventInfo^ eventInfo, 
	Component^ target, 
	String^ handlerName
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member RemoveEventHandler : 
        eventInfo : EventInfo * 
        target : Component * 
        handlerName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>eventInfo</dt><dd>Type: System.Reflection.EventInfo<br />The event information.</dd><dt>target</dt><dd>Type: System.ComponentModel.Component<br />The event source.</dd><dt>handlerName</dt><dd>Type: System.String<br />The name of the delegate to be disassociated from the events raised by *target*. 

 Note: the name is case-sensitive.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type EventInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1

    Private Sub Form1_Load(sender As Object, e As EventArgs) Handles MyBase.Shown
        Dim target As Form = Me
        Dim eventInfo As EventInfo = target.GetType().GetEvent(NameOf(Form.Click))
        eventInfo.RemoveEventHandler(target, NameOf(Me.Form1_Click))
    End Sub

    Private Sub Form1_Click(sender As Object, e As EventArgs) Handles MyBase.Click
        MsgBox(MethodBase.GetCurrentMethod().Name)
    End Sub

End Class
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_EventInfo_EventInfoExtensions">EventInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_EventInfo">DevCase.Core.Extensions.EventInfo Namespace</a><br />