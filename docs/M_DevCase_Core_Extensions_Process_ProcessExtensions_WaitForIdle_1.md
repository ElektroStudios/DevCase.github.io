# ProcessExtensions.WaitForIdle Method (Process, Int32)
 

Causes the Process component to wait for the specified amount of time, in milliseconds, until the user interface has been fully loaded then entered in IDLE state. 

 This applies only to processes with a user interface and, therefore, a message loop.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Process">DevCase.Core.Extensions.Process</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void WaitForIdle(
	this Process sender,
	int checkInterval
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub WaitForIdle ( 
	sender As Process,
	checkInterval As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As Process
Dim checkInterval As Integer

sender.WaitForIdle(checkInterval)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void WaitForIdle(
	Process^ sender, 
	int checkInterval
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member WaitForIdle : 
        sender : Process * 
        checkInterval : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Diagnostics.Process<br />The source Process.</dd><dt>checkInterval</dt><dd>Type: System.Int32<br />The interval, in milliseconds, to check the parameters that determines whether the user-interface has been loaded and the preocess entered in IDLE state. 

 It is recommended to experiment with a value between `1000` and `2000` ms, smaller values could give unexpected results.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Process. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Using p As New Process
    p.StartInfo.FileName = "C:\Program Files\Photoshop\Photoshop.exe"
    p.Start()
    p.WaitForIdle(checkInterval:=1500)
End Using

MsgBox("Process's UI has been fully loaded.")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Process_ProcessExtensions">ProcessExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Process_ProcessExtensions_WaitForIdle">WaitForIdle Overload</a><br /><a href="N_DevCase_Core_Extensions_Process">DevCase.Core.Extensions.Process Namespace</a><br />