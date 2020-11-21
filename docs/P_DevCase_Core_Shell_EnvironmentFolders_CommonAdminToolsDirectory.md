# EnvironmentFolders.CommonAdminToolsDirectory Property 
 

Gets the file system directory that contains administrative tools for all users of the compute. 

 Typically: 'C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Administrative Tools'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo CommonAdminToolsDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CommonAdminToolsDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.CommonAdminToolsDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ CommonAdminToolsDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member CommonAdminToolsDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.CommonAdminToolsDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.CommonAdminToolsDirectory)}={EnvironmentFolders.CommonAdminToolsDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />