# EnvironmentFolders.PrinterShortcutsDirectory Property 
 

Gets the file system directory that contains the link objects that can exist in the Printers virtual folder. 

 Typically: 'C:\Users\{USERNAME}\AppData\Roaming\Microsoft\Windows\Printer Shortcuts'

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo PrinterShortcutsDirectory { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property PrinterShortcutsDirectory As DirectoryInfo
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As DirectoryInfo

value = EnvironmentFolders.PrinterShortcutsDirectory

```

**C++**<br />
``` C++
public:
static property DirectoryInfo^ PrinterShortcutsDirectory {
	DirectoryInfo^ get ();
}
```

**F#**<br />
``` F#
static member PrinterShortcutsDirectory : DirectoryInfo with get

```


#### Property Value
Type: DirectoryInfo<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.EnvironmentFolders.PrinterShortcutsDirectory"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine($"{NameOf(EnvironmentFolders.PrinterShortcutsDirectory)}={EnvironmentFolders.PrinterShortcutsDirectory.FullName}")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_EnvironmentFolders">EnvironmentFolders Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />