# EnvironmentFolders.MyDocumentsDirectory Property 
 

Gets the My Documents folder. 

 Typically: 'C:\Users\{USERNAME}\Documents'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo MyDocumentsDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property MyDocumentsDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.MyDocumentsDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ MyDocumentsDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member MyDocumentsDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.MyDocumentsDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.MyDocumentsDirectory)}={EnvironmentFolders.MyDocumentsDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />