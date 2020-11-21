# EnvironmentFolders.FavoritesDirectory Property 
 

Gets the directory that serves as a common repository for the user's favorite items. 

 Typically: 'C:\Users\{USERNAME}\Favorites'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo FavoritesDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property FavoritesDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.FavoritesDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ FavoritesDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member FavoritesDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.FavoritesDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.FavoritesDirectory)}={EnvironmentFolders.FavoritesDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />