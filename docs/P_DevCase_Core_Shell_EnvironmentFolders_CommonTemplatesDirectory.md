# EnvironmentFolders.CommonTemplatesDirectory Property 
 

Gets the file system directory that contains the templates that are available to all users. 

 Typically: 'C:\ProgramData\Microsoft\Windows\Templates'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo CommonTemplatesDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CommonTemplatesDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.CommonTemplatesDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ CommonTemplatesDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member CommonTemplatesDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.CommonTemplatesDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.CommonTemplatesDirectory)}={EnvironmentFolders.CommonTemplatesDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />