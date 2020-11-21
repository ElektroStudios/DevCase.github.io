# EnvironmentFolders.CommonProgramFilesDirectory Property 
 

Gets the the directory for components that are shared across applications. 

 Typically: 'C:\Program Files\Common Files'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo CommonProgramFilesDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CommonProgramFilesDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.CommonProgramFilesDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ CommonProgramFilesDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member CommonProgramFilesDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.CommonProgramFilesDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.CommonProgramFilesDirectory)}={EnvironmentFolders.CommonProgramFilesDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />