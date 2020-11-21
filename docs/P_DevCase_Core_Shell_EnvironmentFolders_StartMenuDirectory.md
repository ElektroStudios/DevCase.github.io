# EnvironmentFolders.StartMenuDirectory Property 
 

Gets the directory that contains the Start menu items. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Start Menu'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo StartMenuDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property StartMenuDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.StartMenuDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ StartMenuDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member StartMenuDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.StartMenuDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.StartMenuDirectory)}={EnvironmentFolders.StartMenuDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />