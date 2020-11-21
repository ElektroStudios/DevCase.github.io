# EnvironmentFolders.ProgramsDirectory Property 
 

Gets the directory that contains the user's program groups. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo ProgramsDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ProgramsDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.ProgramsDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ ProgramsDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member ProgramsDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.ProgramsDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.ProgramsDirectory)}={EnvironmentFolders.ProgramsDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />