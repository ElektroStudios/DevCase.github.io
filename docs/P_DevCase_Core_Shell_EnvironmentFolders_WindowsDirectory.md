# EnvironmentFolders.WindowsDirectory Property 
 

Gets the Windows directory or SYSROOT. 

 Typically: 'C:\Windows'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo WindowsDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property WindowsDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.WindowsDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ WindowsDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member WindowsDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.WindowsDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.WindowsDirectory)}={EnvironmentFolders.WindowsDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />