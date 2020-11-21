# FileInfoExtensions.HasRights Method 
 

Determines whether the source file contains the specified user-rights.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool HasRights(
	this FileInfo sender,
	FileSystemRights rights,
	AccessControlType accessControlType
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function HasRights ( 
	sender As FileInfo,
	rights As FileSystemRights,
	accessControlType As AccessControlType
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As FileInfo
Dim rights As FileSystemRights
Dim accessControlType As AccessControlType
Dim returnValue As Boolean

returnValue = sender.HasRights(rights, 
	accessControlType)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool HasRights(
	FileInfo^ sender, 
	FileSystemRights rights, 
	AccessControlType accessControlType
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member HasRights : 
        sender : FileInfo * 
        rights : FileSystemRights * 
        accessControlType : AccessControlType -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.FileInfo<br />The source FileInfo.</dd><dt>rights</dt><dd>Type: System.Security.AccessControl.FileSystemRights<br />The user-rights.</dd><dt>accessControlType</dt><dd>Type: System.Security.AccessControl.AccessControlType<br />The access control type, determines whether to check for allowed user-rights or denied user-rights.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the file contains the user-rights; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type FileInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\File.ext")
Dim hasRights As Boolean = file.HasRights(FileSystemRights.Read Or FileSystemRights.Write, AccessControlType.Allow)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_FileInfo_FileInfoExtensions">FileInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo Namespace</a><br />