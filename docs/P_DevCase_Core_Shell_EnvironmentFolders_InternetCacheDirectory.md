# EnvironmentFolders.InternetCacheDirectory Property 
 

Gets the directory that serves as a common repository for temporary Internet files. 

 Typically: 'C:\Users\{USERNAME}\AppData\Local\Microsoft\Windows\INetCache'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo InternetCacheDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property InternetCacheDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.InternetCacheDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ InternetCacheDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member InternetCacheDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.InternetCacheDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.InternetCacheDirectory)}={EnvironmentFolders.InternetCacheDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />