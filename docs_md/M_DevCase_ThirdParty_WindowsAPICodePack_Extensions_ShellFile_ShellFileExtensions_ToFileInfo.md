# ShellFileExtensions.ToFileInfo Method 
 

Converts the specified ShellFile to FileInfo.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_WindowsAPICodePack_Extensions_ShellFile">DevCase.ThirdParty.WindowsAPICodePack.Extensions.ShellFile</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static FileInfo ToFileInfo(
	this ShellFile sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToFileInfo ( 
	sender As ShellFile
) As FileInfo
```

**VB Usage**<br />
``` VB Usage
Dim sender As ShellFile
Dim returnValue As FileInfo

returnValue = sender.ToFileInfo()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static FileInfo^ ToFileInfo(
	ShellFile^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToFileInfo : 
        sender : ShellFile -> FileInfo 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: ShellFile<br />The source ShellFile.</dd></dl>

#### Return Value
Type: FileInfo<br />The resulting FileInfo

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ShellFile. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_WindowsAPICodePack_Extensions_ShellFile_ShellFileExtensions">ShellFileExtensions Class</a><br /><a href="N_DevCase_ThirdParty_WindowsAPICodePack_Extensions_ShellFile">DevCase.ThirdParty.WindowsAPICodePack.Extensions.ShellFile Namespace</a><br />