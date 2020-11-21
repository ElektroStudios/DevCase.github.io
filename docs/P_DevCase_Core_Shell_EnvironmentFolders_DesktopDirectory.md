# EnvironmentFolders.DesktopDirectory Property 
 

Gets the directory used to physically store file objects on the desktop. 

 Typically: 'C:\Users\{USERNAME}\Desktop'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo DesktopDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property DesktopDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.DesktopDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ DesktopDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member DesktopDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.DesktopDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.DesktopDirectory)}={EnvironmentFolders.DesktopDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />