# EnvironmentFolders.MyMusicDirectory Property 
 

Gets the My Music folder. 

 Typically: 'C:\Users\{USERNAME}\Music'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo MyMusicDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property MyMusicDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.MyMusicDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ MyMusicDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member MyMusicDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.MyMusicDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.MyMusicDirectory)}={EnvironmentFolders.MyMusicDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />