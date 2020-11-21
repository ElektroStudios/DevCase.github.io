# EnvironmentFolders.CommonProgramFilesX86Directory Property 
 

Gets the the Program Files folder. 

 Typically: 'C:\Program Files (x86)\Common Files'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo CommonProgramFilesX86Directory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CommonProgramFilesX86Directory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.CommonProgramFilesX86Directory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ CommonProgramFilesX86Directory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member CommonProgramFilesX86Directory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.CommonProgramFilesX86Directory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.CommonProgramFilesX86Directory)}={EnvironmentFolders.CommonProgramFilesX86Directory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />