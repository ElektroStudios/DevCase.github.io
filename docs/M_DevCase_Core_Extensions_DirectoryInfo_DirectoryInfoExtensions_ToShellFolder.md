# DirectoryInfoExtensions.ToShellFolder Method 
 

Converts the specified DirectoryInfo to ShellFolder.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static ShellFolder ToShellFolder(
	this DirectoryInfo sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToShellFolder ( 
	sender As DirectoryInfo
) As ShellFolder
```

**VB Usage**<br />
``` VB Usage
Dim sender As DirectoryInfo
Dim returnValue As ShellFolder

returnValue = sender.ToShellFolder()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static ShellFolder^ ToShellFolder(
	DirectoryInfo^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToShellFolder : 
        sender : DirectoryInfo -> ShellFolder 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.DirectoryInfo<br />The source DirectoryInfo.</dd></dl>

#### Return Value
Type: ShellFolder<br />The resulting ShellFolder

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DirectoryInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
For Each dir As DirectoryInfo In New DirectoryInfo("C:\Directory\").GetDirectories("*", SearchOption.TopDirectoryOnly)
    Dim sFolder As ShellFolder = dir.ToShellFolder()
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions">DirectoryInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo Namespace</a><br />