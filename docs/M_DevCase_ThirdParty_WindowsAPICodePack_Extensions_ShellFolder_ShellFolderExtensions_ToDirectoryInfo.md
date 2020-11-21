# ShellFolderExtensions.ToDirectoryInfo Method 
 

Converts the specified ShellFolder to DirectoryInfo.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_WindowsAPICodePack_Extensions_ShellFolder">DevCase.ThirdParty.WindowsAPICodePack.Extensions.ShellFolder</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static DirectoryInfo ToDirectoryInfo(
	this ShellFolder sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToDirectoryInfo ( 
	sender As ShellFolder
) As DirectoryInfo
```

**VB Usage**<br />
``` VB Usage
Dim sender As ShellFolder
Dim returnValue As DirectoryInfo

returnValue = sender.ToDirectoryInfo()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static DirectoryInfo^ ToDirectoryInfo(
	ShellFolder^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToDirectoryInfo : 
        sender : ShellFolder -> DirectoryInfo 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: ShellFolder<br />The source ShellFolder.</dd></dl>

#### Return Value
Type: DirectoryInfo<br />The resulting DirectoryInfo

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ShellFolder. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_WindowsAPICodePack_Extensions_ShellFolder_ShellFolderExtensions">ShellFolderExtensions Class</a><br /><a href="N_DevCase_ThirdParty_WindowsAPICodePack_Extensions_ShellFolder">DevCase.ThirdParty.WindowsAPICodePack.Extensions.ShellFolder Namespace</a><br />