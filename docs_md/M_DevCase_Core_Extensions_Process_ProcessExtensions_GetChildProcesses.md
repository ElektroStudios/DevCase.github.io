# ProcessExtensions.GetChildProcesses Method 
 

Gets the child processes of the source Process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Process">DevCase.Core.Extensions.Process</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<Process> GetChildProcesses(
	this Process sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetChildProcesses ( 
	sender As Process
) As IEnumerable(Of Process)
```

**VB Usage**<br />
``` VB Usage
Dim sender As Process
Dim returnValue As IEnumerable(Of Process)

returnValue = sender.GetChildProcesses()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IEnumerable<Process^>^ GetChildProcesses(
	Process^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetChildProcesses : 
        sender : Process -> IEnumerable<Process> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Diagnostics.Process<br />The source Process.</dd></dl>

#### Return Value
Type: IEnumerable(Process)<br />A IEnumerable(T) containing the child processes.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Process. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mainProcess As Process = Process.GetProcessesByName("explorer").Single()
Dim childProcesses As IEnumerable(Of Process) = mainProcess.GetChildProcesses()

For Each p As Process In childProcesses
    Console.WriteLine(p.ProcessName)
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Process_ProcessExtensions">ProcessExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Process">DevCase.Core.Extensions.Process Namespace</a><br />