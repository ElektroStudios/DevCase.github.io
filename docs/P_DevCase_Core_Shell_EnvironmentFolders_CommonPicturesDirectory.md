# EnvironmentFolders.CommonPicturesDirectory Property 
 

Gets the file system directory that serves as a repository for image files common to all users. 

 Typically: 'C:\Users\Public\Pictures'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo CommonPicturesDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CommonPicturesDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.CommonPicturesDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ CommonPicturesDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member CommonPicturesDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.CommonPicturesDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.CommonPicturesDirectory)}={EnvironmentFolders.CommonPicturesDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />