# ProcessExtensions.WaitForIdleAsync Method (Process, Action)
 

Aynchronouslly causes the Process component to wait indefinitely until the user interface has been fully loaded then entered in IDLE state. 

 This applies only to processes with a user interface and, therefore, a message loop.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Process">DevCase.Core.Extensions.Process</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void WaitForIdleAsync(
	this Process sender,
	Action callback
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub WaitForIdleAsync ( 
	sender As Process,
	callback As Action
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As Process
Dim callback As Action

sender.WaitForIdleAsync(callback)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void WaitForIdleAsync(
	Process^ sender, 
	Action^ callback
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member WaitForIdleAsync : 
        sender : Process * 
        callback : Action -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Diagnostics.Process<br />The source Process.</dd><dt>callback</dt><dd>Type: System.Action<br />A <a href="N_DevCase_Core_Extensions_Action">DevCase.Core.Extensions.Action</a> delegate which will be invoked inmmediately after the process is fully loaded and entered in IDLE state. 

 When WaitForIdleAsync(Process, Action) method is called from a UI thread, *callback* is invoked on the same UI thread.</dd></dl>

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
        p.WaitForIdleAsync(p, AddressOf WaitForIdleAsync_CallBack)
    End Using

End Sub

Private Sub WaitForIdleAsync_CallBack()
    MsgBox("Process's UI has been fully loaded.")
End Sub
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Process_ProcessExtensions">ProcessExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Process_ProcessExtensions_WaitForIdleAsync">WaitForIdleAsync Overload</a><br /><a href="N_DevCase_Core_Extensions_Process">DevCase.Core.Extensions.Process Namespace</a><br />