# DirectoryUtil.SetRights Method (DirectoryInfo, FileSystemRights, AccessControlType)
 

Sets the user-rights of a directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetRights(
	DirectoryInfo directory,
	FileSystemRights rights,
	AccessControlType accessControlType
)
```

**VB**<br />
``` VB
Public Shared Sub SetRights ( 
	directory As DirectoryInfo,
	rights As FileSystemRights,
	accessControlType As AccessControlType
)
```

**VB Usage**<br />
``` VB Usage
Dim directory As DirectoryInfo
Dim rights As FileSystemRights
Dim accessControlType As AccessControlTypeDirectoryUtil.SetRights(directory, rights, 
	accessControlType)
```

**C++**<br />
``` C++
public:
static void SetRights(
	DirectoryInfo^ directory, 
	FileSystemRights rights, 
	AccessControlType accessControlType
)
```

**F#**<br />
``` F#
static member SetRights : 
        directory : DirectoryInfo * 
        rights : FileSystemRights * 
        accessControlType : AccessControlType -> unit 

```


#### Parameters
&nbsp;<dl><dt>directory</dt><dd>Type: System.IO.DirectoryInfo<br />The source directory.</dd><dt>rights</dt><dd>Type: System.Security.AccessControl.FileSystemRights<br />The user-rights.</dd><dt>accessControlType</dt><dd>Type: System.Security.AccessControl.AccessControlType<br />The access control type, determines whether to allowe user-rights or deny user-rights.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dir As New DirectoryInfo("C:\Directory\")
SetRights(dir, FileSystemRights.FullControl, AccessControlType.Allow)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DirectoryUtil_SetRights">SetRights Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />