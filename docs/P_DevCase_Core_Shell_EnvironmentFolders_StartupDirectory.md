# EnvironmentFolders.StartupDirectory Property 
 

Gets the directory that corresponds to the user's Startup program group. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo StartupDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property StartupDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.StartupDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ StartupDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member StartupDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.StartupDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.StartupDirectory)}={EnvironmentFolders.StartupDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />