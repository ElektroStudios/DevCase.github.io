# EnvironmentFolders.CommonStartupDirectory Property 
 

Gets the file system directory that contains the programs that appear in the Startup folder for all users. 

 Typically: 'C:\ProgramData\Microsoft\Windows\Start Menu'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo CommonStartupDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CommonStartupDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.CommonStartupDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ CommonStartupDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member CommonStartupDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.CommonStartupDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.CommonStartupDirectory)}={EnvironmentFolders.CommonStartupDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />