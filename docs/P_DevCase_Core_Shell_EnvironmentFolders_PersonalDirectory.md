# EnvironmentFolders.PersonalDirectory Property 
 

Gets the directory that serves as a common repository for documents. 

 Typically: 'C:\Users\{USERNAME}\Documents'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo PersonalDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property PersonalDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.PersonalDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ PersonalDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member PersonalDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.PersonalDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.PersonalDirectory)}={EnvironmentFolders.PersonalDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />