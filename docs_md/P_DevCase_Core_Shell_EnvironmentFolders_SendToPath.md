# EnvironmentFolders.SendToPath Property 
 

Gets the full path to the directory that contains the Send To menu items. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\SendTo'

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
Public Shared ReadOnly Property SendToPath ( 
	Optional folderOption As Environment.SpecialFolderOption = Environment.SpecialFolderOption.None
) As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim folderOption As Environment.SpecialFolderOption
Dim value As String

value = EnvironmentFolders.SendToPath(folderOption)

```

**C++**<br />
``` C++
public:
static property String^ SendToPath[Environment.SpecialFolderOption folderOption = Environment.SpecialFolderOption::None] {
	String^ get (Environment.SpecialFolderOption folderOption = Environment.SpecialFolderOption::None);
}
```

**F#**<br />
``` F#
static member SendToPath : string with get

```


#### Parameters
&nbsp;<dl><dt>folderOption (Optional)</dt><dd>Type: System.Environment.SpecialFolderOption<br /></dd></dl>

#### Property Value
Type: String<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.SendToPath(System.Environment.SpecialFolderOption)"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.SendToPath)}={EnvironmentFolders.SendToPath}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />