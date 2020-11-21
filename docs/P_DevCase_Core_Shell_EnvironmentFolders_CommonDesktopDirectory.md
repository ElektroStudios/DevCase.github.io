# EnvironmentFolders.CommonDesktopDirectory Property 
 

Gets the file system directory that contains files and folders that appear on the desktop for all users. 

 Typically: 'C:\Users\Public\Desktop'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo CommonDesktopDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CommonDesktopDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.CommonDesktopDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ CommonDesktopDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member CommonDesktopDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.CommonDesktopDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.CommonDesktopDirectory)}={EnvironmentFolders.CommonDesktopDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />