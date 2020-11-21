# EnvironmentFolders.NetworkShortcutsDirectory Property 
 

Gets the file system directory that contains the link objects that may exist in the My Network Places virtual folder. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Network Shortcuts'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo NetworkShortcutsDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property NetworkShortcutsDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.NetworkShortcutsDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ NetworkShortcutsDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member NetworkShortcutsDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.NetworkShortcutsDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.NetworkShortcutsDirectory)}={EnvironmentFolders.NetworkShortcutsDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />