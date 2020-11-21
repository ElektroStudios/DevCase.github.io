# ProcessExtensions.GetParentProcess Method 
 

Gets the parent process that created the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Process">DevCase.Core.Extensions.Process</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Process GetParentProcess(
	this Process pr
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetParentProcess ( 
	pr As Process
) As Process
```

**VB Usage**<br />
``` VB Usage
Dim pr As Process
Dim returnValue As Process

returnValue = pr.GetParentProcess()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Process^ GetParentProcess(
	Process^ pr
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetParentProcess : 
        pr : Process -> Process 

```


#### Parameters
&nbsp;<dl><dt>pr</dt><dd>Type: System.Diagnostics.Process<br />The source Process.</dd></dl>

#### Return Value
Type: Process<br />The parent process that created the specified process, or a null reference (`Nothing` in Visual Basic) if the parent process has exited.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Process. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pr As Process = Process.GetCurrentProcess()
Dim parent As Process = GetParentProcess(pr)

Console.WriteLine(parent.ProcessName)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Process_ProcessExtensions">ProcessExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Process">DevCase.Core.Extensions.Process Namespace</a><br />