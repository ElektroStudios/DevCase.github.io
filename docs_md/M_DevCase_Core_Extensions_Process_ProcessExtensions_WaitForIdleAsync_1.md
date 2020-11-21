# ProcessExtensions.WaitForIdleAsync Method (Process, Action, Int32)
 

Aynchronouslly causes the Process component to wait for the specified amount of time, in milliseconds, until the user interface has been fully loaded then entered in IDLE state. 

 This applies only to processes with a user interface and, therefore, a message loop.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Process">DevCase.Core.Extensions.Process</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void WaitForIdleAsync(
	this Process sender,
	Action callback,
	int checkInterval
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub WaitForIdleAsync ( 
	sender As Process,
	callback As Action,
	checkInterval As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As Process
Dim callback As Action
Dim checkInterval As Integer

sender.WaitForIdleAsync(callback, 
	checkInterval)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void WaitForIdleAsync(
	Process^ sender, 
	Action^ callback, 
	int checkInterval
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member WaitForIdleAsync : 
        sender : Process * 
        callback : Action * 
        checkInterval : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Diagnostics.Process<br />The source Process.</dd><dt>callback</dt><dd>Type: System.Action<br />A <a href="N_DevCase_Core_Extensions_Action">DevCase.Core.Extensions.Action</a> delegate that will be invoked inmmediately after the process is fully loaded and entered in IDLE state. 

 When <a href="M_DevCase_Core_Extensions_Process_ProcessExtensions_WaitForIdleAsync">WaitForIdleAsync(Process, Action)</a> method is called from a UI thread, *callback* is invoked on the same UI thread.</dd><dt>checkInterval</dt><dd>Type: System.Int32<br />The interval, in milliseconds, to check the parameters that determines whether the user-interface has been loaded and the preocess entered in IDLE state. 

 It is recommended to experiment with a value between `1000` and `2000` ms, smaller values could give unexpected results.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Process. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Private Sub Test()

    Using p As New Process
        p.StartInfo.FileName = "C:\Program Files\Photoshop\Photoshop.exe"
        p.Start()
        p.WaitForIdleAsync(p, AddressOf WaitForIdleAsync_CallBack, checkInterval:=1500)
    End Using

End Sub

Private Sub WaitForIdleAsync_CallBack()
    MsgBox("Process's UI has been fully loaded.")
End Sub
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Process_ProcessExtensions">ProcessExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Process_ProcessExtensions_WaitForIdleAsync">WaitForIdleAsync Overload</a><br /><a href="N_DevCase_Core_Extensions_Process">DevCase.Core.Extensions.Process Namespace</a><br />