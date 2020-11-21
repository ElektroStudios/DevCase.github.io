# EnvironmentFolders.LocalApplicationDataDirectory Property 
 

Gets the directory that serves as a common repository for application-specific data that is used by the current, non-roaming user. 

 Typically: 'C:\Users\{USERNAME}\AppData\Local'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo LocalApplicationDataDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property LocalApplicationDataDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.LocalApplicationDataDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ LocalApplicationDataDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member LocalApplicationDataDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.LocalApplicationDataDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.LocalApplicationDataDirectory)}={EnvironmentFolders.LocalApplicationDataDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />