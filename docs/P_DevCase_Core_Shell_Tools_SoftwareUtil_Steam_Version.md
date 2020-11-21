# SoftwareUtil.Steam.Version Property 
 

Gets the version of the Steam client installed on the current Operating System.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Version Version { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property Version As Version
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Version

value = SoftwareUtil.Steam.Version

```

**C++**<br />
``` C++
public:
static property Version^ Version {
	Version^ get ();
}
```

**F#**<br />
``` F#
static member Version : Version with get

```


#### Property Value
Type: Version<br />If Steam is not installed, the return value is a null reference (`Nothing` in Visual Basic), otherwise, the client version.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Steam">SoftwareUtil.Steam Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />