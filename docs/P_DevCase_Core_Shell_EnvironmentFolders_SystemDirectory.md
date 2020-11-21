# EnvironmentFolders.SystemDirectory Property 
 

Gets the System directory. 

 Typically: 'C:\Windows\System32'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo SystemDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property SystemDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.SystemDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ SystemDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member SystemDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.SystemDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.SystemDirectory)}={EnvironmentFolders.SystemDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />