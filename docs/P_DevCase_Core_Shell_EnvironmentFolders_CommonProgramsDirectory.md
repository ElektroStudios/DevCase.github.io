# EnvironmentFolders.CommonProgramsDirectory Property 
 

Gets the folder for components that are shared across applications. 

 Typically: 'C:\ProgramData\Microsoft\Windows\Start Menu\Programs'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo CommonProgramsDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CommonProgramsDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.CommonProgramsDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ CommonProgramsDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member CommonProgramsDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.CommonProgramsDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.CommonProgramsDirectory)}={EnvironmentFolders.CommonProgramsDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />