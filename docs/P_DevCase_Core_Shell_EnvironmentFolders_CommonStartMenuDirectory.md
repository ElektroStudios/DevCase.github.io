# EnvironmentFolders.CommonStartMenuDirectory Property 
 

Gets the file system directory that contains the programs and folders that appear on the Start menu for all users. 

 Typically: 'C:\ProgramData\Microsoft\Windows\Start Menu'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo CommonStartMenuDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CommonStartMenuDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.CommonStartMenuDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ CommonStartMenuDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member CommonStartMenuDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.CommonStartMenuDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.CommonStartMenuDirectory)}={EnvironmentFolders.CommonStartMenuDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />