# EnvironmentFolders.ProgramFilesDirectory Property 
 

Gets the program files directory. 

 Typically: 'C:\Program Files'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo ProgramFilesDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ProgramFilesDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.ProgramFilesDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ ProgramFilesDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member ProgramFilesDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.ProgramFilesDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.ProgramFilesDirectory)}={EnvironmentFolders.ProgramFilesDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />