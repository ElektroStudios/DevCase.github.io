# WindowsUtil.TaskManagerHijack Property 
 

Determines whether the legit 'taskmgr.exe' file has a hijack defined in the Windows registry, then returns the registry value that points to the hijack file path.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string TaskManagerHijack { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property TaskManagerHijack As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = WindowsUtil.TaskManagerHijack

```

**C++**<br />
``` C++
public:
static property String^ TaskManagerHijack {
	String^ get ();
}
```

**F#**<br />
``` F#
static member TaskManagerHijack : string with get

```


#### Property Value
Type: String<br />The resulting hijack registry value, or a null reference (`Nothing` in Visual Basic) (null) if a 'taskmgr.exe' hijack is not defined on the system.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_WindowsUtil">WindowsUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />