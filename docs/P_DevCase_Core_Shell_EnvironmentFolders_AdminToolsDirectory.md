# EnvironmentFolders.AdminToolsDirectory Property 
 

Gets the file system directory that is used to store administrative tools for an individual user. 

 The Microsoft Management Console (MMC) will save customized consoles to this directory, and it will roam with the user. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Administrative Tools'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo AdminToolsDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property AdminToolsDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.AdminToolsDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ AdminToolsDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member AdminToolsDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.AdminToolsDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.AdminToolsDirectory)}={EnvironmentFolders.AdminToolsDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />