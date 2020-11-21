# EnvironmentFolders.SendToDirectory Property 
 

Gets the directory that contains the Send To menu items. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\SendTo'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo SendToDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property SendToDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.SendToDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ SendToDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member SendToDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.SendToDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.SendToDirectory)}={EnvironmentFolders.SendToDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />