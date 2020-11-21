# ExplorerUtil.Windows Property 
 

Gets a ReadOnlyCollection(T) containing the opened windows explorer instances.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<ShellBrowserWindow> Windows { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property Windows As ReadOnlyCollection(Of ShellBrowserWindow)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As ReadOnlyCollection(Of ShellBrowserWindow)

value = ExplorerUtil.Windows

```

**C++**<br />
``` C++
public:
static property ReadOnlyCollection<ShellBrowserWindow^>^ Windows {
	ReadOnlyCollection<ShellBrowserWindow^>^ get ();
}
```

**F#**<br />
``` F#
static member Windows : ReadOnlyCollection<ShellBrowserWindow> with get

```


#### Property Value
Type: ReadOnlyCollection(ShellBrowserWindow)<br />A ReadOnlyCollection(T) containing the opened windows explorer instances.

## Examples
This is a code example. 
**VB**<br />
``` VB
For Each window As ShellBrowserWindow In Windows()
    Console.WriteLine(window.LocationURL)
Next window
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ExplorerUtil">ExplorerUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />