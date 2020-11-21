# ExplorerUtil.Folders Property 
 

Gets a ReadOnlyCollection(T) containing the opened windows explorer folder instances.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<Folder2> Folders { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property Folders As ReadOnlyCollection(Of Folder2)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As ReadOnlyCollection(Of Folder2)

value = ExplorerUtil.Folders

```

**C++**<br />
``` C++
public:
static property ReadOnlyCollection<Folder2^>^ Folders {
	ReadOnlyCollection<Folder2^>^ get ();
}
```

**F#**<br />
``` F#
static member Folders : ReadOnlyCollection<Folder2> with get

```


#### Property Value
Type: ReadOnlyCollection(Folder2)<br />A ReadOnlyCollection(T) containing the opened windows explorer folder instances.

## Examples
This is a code example. 
**VB**<br />
``` VB
For Each folder As Folder2 In Folders()
    Console.WriteLine(folder.Self.Path)
Next folder
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ExplorerUtil">ExplorerUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />