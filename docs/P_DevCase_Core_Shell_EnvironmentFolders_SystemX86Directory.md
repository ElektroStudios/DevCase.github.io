# EnvironmentFolders.SystemX86Directory Property 
 

Gets the Windows System folder. 

 Typically: 'C:\Windows\SysWOW64'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo SystemX86Directory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property SystemX86Directory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.SystemX86Directory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ SystemX86Directory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member SystemX86Directory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.SystemX86Directory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.SystemX86Directory)}={EnvironmentFolders.SystemX86Directory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />