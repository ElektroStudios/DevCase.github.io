# FileUtil.SetRights Method (FileInfo, FileSystemRights, AccessControlType)
 

Sets the user-rights of a file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetRights(
	FileInfo file,
	FileSystemRights rights,
	AccessControlType accessControlType
)
```

**VB**<br />
``` VB
Public Shared Sub SetRights ( 
	file As FileInfo,
	rights As FileSystemRights,
	accessControlType As AccessControlType
)
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim rights As FileSystemRights
Dim accessControlType As AccessControlTypeFileUtil.SetRights(file, rights, accessControlType)
```

**C++**<br />
``` C++
public:
static void SetRights(
	FileInfo^ file, 
	FileSystemRights rights, 
	AccessControlType accessControlType
)
```

**F#**<br />
``` F#
static member SetRights : 
        file : FileInfo * 
        rights : FileSystemRights * 
        accessControlType : AccessControlType -> unit 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The source file.</dd><dt>rights</dt><dd>Type: System.Security.AccessControl.FileSystemRights<br />The user-rights.</dd><dt>accessControlType</dt><dd>Type: System.Security.AccessControl.AccessControlType<br />The access control type, determines whether to allowe user-rights or deny user-rights.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\File.ext")
SetRights(file, FileSystemRights.Read Or FileSystemRights.Write, AccessControlType.Allow)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_SetRights">SetRights Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />