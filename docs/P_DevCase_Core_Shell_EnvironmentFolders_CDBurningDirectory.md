# EnvironmentFolders.CDBurningDirectory Property 
 

Gets the file system directory that acts as a staging area for files waiting to be written to a CD. 

 Typically: 'C:\Users\{USERNAME}\AppData\Local\Microsoft\Windows\Burn\Burn'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo CDBurningDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CDBurningDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.CDBurningDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ CDBurningDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member CDBurningDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.CDBurningDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.CDBurningDirectory)}={EnvironmentFolders.CDBurningDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />