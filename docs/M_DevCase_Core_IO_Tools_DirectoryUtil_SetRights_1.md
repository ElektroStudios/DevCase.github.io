# DirectoryUtil.SetRights Method (String, FileSystemRights, AccessControlType)
 

Sets the user-rights of a directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetRights(
	string directoryPath,
	FileSystemRights rights,
	AccessControlType accessControlType
)
```

**VB**<br />
``` VB
Public Shared Sub SetRights ( 
	directoryPath As String,
	rights As FileSystemRights,
	accessControlType As AccessControlType
)
```

**VB Usage**<br />
``` VB Usage
Dim directoryPath As String
Dim rights As FileSystemRights
Dim accessControlType As AccessControlTypeDirectoryUtil.SetRights(directoryPath, rights, 
	accessControlType)
```

**C++**<br />
``` C++
public:
static void SetRights(
	String^ directoryPath, 
	FileSystemRights rights, 
	AccessControlType accessControlType
)
```

**F#**<br />
``` F#
static member SetRights : 
        directoryPath : string * 
        rights : FileSystemRights * 
        accessControlType : AccessControlType -> unit 

```


#### Parameters
&nbsp;<dl><dt>directoryPath</dt><dd>Type: System.String<br />The directory path.</dd><dt>rights</dt><dd>Type: System.Security.AccessControl.FileSystemRights<br />The user-rights.</dd><dt>accessControlType</dt><dd>Type: System.Security.AccessControl.AccessControlType<br />The access control type, determines whether to allowe user-rights or deny user-rights.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
SetRights("C:\Directory\", FileSystemRights.FullControl, AccessControlType.Allow)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DirectoryUtil_SetRights">SetRights Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />