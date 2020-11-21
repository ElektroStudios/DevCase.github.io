# WindowsUtil.CurrentArchitecture Property 
 

Determines whether the architecture of the current operating system is 32 or 64 Bits.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static OsArchitecture CurrentArchitecture { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CurrentArchitecture As OsArchitecture
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As OsArchitecture

value = WindowsUtil.CurrentArchitecture

```

**C++**<br />
``` C++
public:
static property OsArchitecture CurrentArchitecture {
	OsArchitecture get ();
}
```

**F#**<br />
``` F#
static member CurrentArchitecture : OsArchitecture with get

```


#### Property Value
Type: <a href="T_DevCase_Core_Shell_OsArchitecture">OsArchitecture</a><br />An <a href="T_DevCase_Core_Shell_OsArchitecture">OsArchitecture</a> object that specifies the architecture of the current operating system.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_WindowsUtil">WindowsUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />