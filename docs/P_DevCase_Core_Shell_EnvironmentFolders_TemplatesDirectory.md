# EnvironmentFolders.TemplatesDirectory Property 
 

Gets the directory that serves as a common repository for document templates. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Templates'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo TemplatesDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property TemplatesDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.TemplatesDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ TemplatesDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member TemplatesDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.TemplatesDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.TemplatesDirectory)}={EnvironmentFolders.TemplatesDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />