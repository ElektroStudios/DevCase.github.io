# SoftwareUtil.Steam.IsInstalled Property 
 

Determines whether Steam client is installed in the current Operating System.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsInstalled { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property IsInstalled As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = SoftwareUtil.Steam.IsInstalled

```

**C++**<br />
``` C++
public:
static property bool IsInstalled {
	bool get ();
}
```

**F#**<br />
``` F#
static member IsInstalled : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if Steam client is installed; `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Steam">SoftwareUtil.Steam Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />