# FolderExtensions.Quit Method 
 

Closes the window instace of the source Folder.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Shell32_Folder">DevCase.Core.Extensions.Shell32.Folder</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void Quit(
	this Folder sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub Quit ( 
	sender As Folder
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As Folder

sender.Quit()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void Quit(
	Folder^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Quit : 
        sender : Folder -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: Folder<br />The source Folder.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Folder. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Shell32_Folder_FolderExtensions">FolderExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Shell32_Folder">DevCase.Core.Extensions.Shell32.Folder Namespace</a><br />