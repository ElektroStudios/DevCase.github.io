# EnvironmentFolders.CommonMusicDirectory Property 
 

Gets the file system directory that serves as a repository for music files common to all users. 

 Typically: 'C:\Users\Public\Music'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo CommonMusicDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CommonMusicDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.CommonMusicDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ CommonMusicDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member CommonMusicDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.CommonMusicDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.CommonMusicDirectory)}={EnvironmentFolders.CommonMusicDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />