# DirectoryInfoExtensions.CopyTo Method (DirectoryInfo, String)
 

Coppies the source directory to the specified directory. 

 If the target directory already exists, an IOException is thrown.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static DirectoryInfo CopyTo(
	this DirectoryInfo sender,
	string targetDirectoryPath
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function CopyTo ( 
	sender As DirectoryInfo,
	targetDirectoryPath As String
) As DirectoryInfo
```

**VB Usage**<br />
``` VB Usage
Dim sender As DirectoryInfo
Dim targetDirectoryPath As String
Dim returnValue As DirectoryInfo

returnValue = sender.CopyTo(targetDirectoryPath)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static DirectoryInfo^ CopyTo(
	DirectoryInfo^ sender, 
	String^ targetDirectoryPath
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CopyTo : 
        sender : DirectoryInfo * 
        targetDirectoryPath : string -> DirectoryInfo 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.DirectoryInfo<br />The source directory.</dd><dt>targetDirectoryPath</dt><dd>Type: System.String<br />The target directory.</dd></dl>

#### Return Value
Type: DirectoryInfo<br />A DirectoryInfo instance that represents the target directory.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DirectoryInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions">DirectoryInfoExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CopyTo">CopyTo Overload</a><br /><a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo Namespace</a><br />