# FileInfoExtensions.HasExtension Method 
 

Determines whether the path includes a file extension.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool HasExtension(
	this FileInfo sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function HasExtension ( 
	sender As FileInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As FileInfo
Dim returnValue As Boolean

returnValue = sender.HasExtension()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool HasExtension(
	FileInfo^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member HasExtension : 
        sender : FileInfo -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.FileInfo<br />The source FileInfo.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the path includes a file extension, otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type FileInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_FileInfo_FileInfoExtensions">FileInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo Namespace</a><br />