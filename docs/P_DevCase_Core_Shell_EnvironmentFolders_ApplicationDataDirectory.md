# EnvironmentFolders.ApplicationDataDirectory Property 
 

Gets the directory that serves as a common repository for application-specific data for the current roaming user. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo ApplicationDataDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ApplicationDataDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.ApplicationDataDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ ApplicationDataDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member ApplicationDataDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.ApplicationDataDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.ApplicationDataDirectory)}={EnvironmentFolders.ApplicationDataDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />