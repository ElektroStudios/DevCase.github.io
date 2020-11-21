# EnvironmentFolders.CommonApplicationDataDirectory Property 
 

Gets the directory that serves as a common repository for application-specific data that is used by all users. 

 Typically: 'C:\ProgramData'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo CommonApplicationDataDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CommonApplicationDataDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.CommonApplicationDataDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ CommonApplicationDataDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member CommonApplicationDataDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.CommonApplicationDataDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.CommonApplicationDataDirectory)}={EnvironmentFolders.CommonApplicationDataDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />