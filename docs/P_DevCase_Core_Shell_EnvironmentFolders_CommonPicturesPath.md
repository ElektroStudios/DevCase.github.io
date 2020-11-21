# EnvironmentFolders.CommonPicturesPath Property 
 

Gets the full path to the file system directory that serves as a repository for image files common to all users. 

 Typically: 'C:\Users\Public\Pictures'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string this[
	Environment.SpecialFolderOption folderOption = Environment.SpecialFolderOption.None
] { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CommonPicturesPath ( 
	Optional folderOption As Environment.SpecialFolderOption = Environment.SpecialFolderOption.None
) As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim folderOption As Environment.SpecialFolderOption
Dim value As String

value = EnvironmentFolders.CommonPicturesPath(folderOption)

```

**C++**<br />
``` C++
public:
static property String^ CommonPicturesPath[Environment.SpecialFolderOption folderOption = Environment.SpecialFolderOption::None] {
	String^ get (Environment.SpecialFolderOption folderOption = Environment.SpecialFolderOption::None);
}
```

**F#**<br />
``` F#
static member CommonPicturesPath : string with get

```


#### Parameters
&nbsp;<dl><dt>folderOption (Optional)</dt><dd>Type: System.Environment.SpecialFolderOption<br /></dd></dl>

#### Property Value
Type: String<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.CommonPicturesPath(System.Environment.SpecialFolderOption)"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.CommonPicturesPath)}={EnvironmentFolders.CommonPicturesPath}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />