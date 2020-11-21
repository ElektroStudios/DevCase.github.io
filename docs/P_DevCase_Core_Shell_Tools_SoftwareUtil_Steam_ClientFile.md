# SoftwareUtil.Steam.ClientFile Property 
 

Gets the executable file of the Steam client installed on the current Operating System.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static FileInfo ClientFile { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ClientFile As FileInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As FileInfo

value = SoftwareUtil.Steam.ClientFile

```

**C++**<br />
``` C++
public:
static property FileInfo^ ClientFile {
	FileInfo^ get ();
}
```

**F#**<br />
``` F#
static member ClientFile : FileInfo with get

```


#### Property Value
Type: FileInfo<br />If Steam is not installed, the return value is a null reference (`Nothing` in Visual Basic), otherwise, the executable file.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Steam">SoftwareUtil.Steam Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />