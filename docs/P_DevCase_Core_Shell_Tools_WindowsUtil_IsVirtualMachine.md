# WindowsUtil.IsVirtualMachine Property 
 

Determines whether the current application is running in a Virtual Machine OS. 

 The detection algorithm is compatible with: 

 Virtual-Box, VMWare, and QEmu.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsVirtualMachine { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property IsVirtualMachine As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = WindowsUtil.IsVirtualMachine

```

**C++**<br />
``` C++
public:
static property bool IsVirtualMachine {
	bool get ();
}
```

**F#**<br />
``` F#
static member IsVirtualMachine : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the current application is running in a Virtual Machine OS, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_WindowsUtil">WindowsUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />