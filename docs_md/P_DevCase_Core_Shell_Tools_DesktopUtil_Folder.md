# DesktopUtil.Folder Property 
 

Gets a Folder2 instance that represents the Desktop virtual folder.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Folder2 Folder { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property Folder As Folder2
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Folder2

value = DesktopUtil.Folder

```

**C++**<br />
``` C++
public:
static property Folder2^ Folder {
	Folder2^ get ();
}
```

**F#**<br />
``` F#
static member Folder : Folder2 with get

```


#### Property Value
Type: Folder2<br />A Folder2 instance that represents the Desktop virtual folder.

## Examples
This is a code example. 
**VB**<br />
``` VB
For Each item As FolderItem In Desktop.Folder.Items
    If (item.IsFileSystem) AndAlso Not (item.IsFolder) Then
        Console.WriteLine(Path.GetFileName(item.Path))
    End If
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_DesktopUtil">DesktopUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />