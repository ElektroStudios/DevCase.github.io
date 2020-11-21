# DirectoryInfoExtensions.SetRights Method 
 

Sets the user-rights of the source directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void SetRights(
	this DirectoryInfo sender,
	FileSystemRights rights,
	AccessControlType accessControlType
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub SetRights ( 
	sender As DirectoryInfo,
	rights As FileSystemRights,
	accessControlType As AccessControlType
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As DirectoryInfo
Dim rights As FileSystemRights
Dim accessControlType As AccessControlType

sender.SetRights(rights, accessControlType)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void SetRights(
	DirectoryInfo^ sender, 
	FileSystemRights rights, 
	AccessControlType accessControlType
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SetRights : 
        sender : DirectoryInfo * 
        rights : FileSystemRights * 
        accessControlType : AccessControlType -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.DirectoryInfo<br />The source DirectoryInfo.</dd><dt>rights</dt><dd>Type: System.Security.AccessControl.FileSystemRights<br />The user-rights.</dd><dt>accessControlType</dt><dd>Type: System.Security.AccessControl.AccessControlType<br />The access control type, determines whether to allowe user-rights or deny user-rights.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DirectoryInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dir As New DirectoryInfo("C:\Directory\")
dir.SetRights(FileSystemRights.FullControl, AccessControlType.Allow)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions">DirectoryInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo Namespace</a><br />