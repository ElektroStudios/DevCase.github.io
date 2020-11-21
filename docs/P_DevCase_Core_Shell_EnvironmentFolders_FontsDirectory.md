# EnvironmentFolders.FontsDirectory Property 
 

Gets the virtual folder that contains fonts. 

 Typically: 'C:\Windows\Fonts'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo FontsDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property FontsDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.FontsDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ FontsDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member FontsDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.FontsDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.FontsDirectory)}={EnvironmentFolders.FontsDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />