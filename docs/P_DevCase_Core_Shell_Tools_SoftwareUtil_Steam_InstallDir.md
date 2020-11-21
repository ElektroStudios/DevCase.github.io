# SoftwareUtil.Steam.InstallDir Property 
 

Gets the installation directory of the Steam client installed on the current Operating System.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo InstallDir { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property InstallDir As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = SoftwareUtil.Steam.InstallDir

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ InstallDir {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member InstallDir : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />If Steam is not installed, the return value is a null reference (`Nothing` in Visual Basic), otherwise, the installation directory.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Steam">SoftwareUtil.Steam Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />