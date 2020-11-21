# DirectoryUtil.HasRights Method (String, FileSystemRights, AccessControlType)
 

Determines whether a directory contains the specified user-rights.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool HasRights(
	string directoryPath,
	FileSystemRights rights,
	AccessControlType accessControlType
)
```

**VB**<br />
``` VB
Public Shared Function HasRights ( 
	directoryPath As String,
	rights As FileSystemRights,
	accessControlType As AccessControlType
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim directoryPath As String
Dim rights As FileSystemRights
Dim accessControlType As AccessControlType
Dim returnValue As Boolean

returnValue = DirectoryUtil.HasRights(directoryPath, 
	rights, accessControlType)
```

**C++**<br />
``` C++
public:
static bool HasRights(
	String^ directoryPath, 
	FileSystemRights rights, 
	AccessControlType accessControlType
)
```

**F#**<br />
``` F#
static member HasRights : 
        directoryPath : string * 
        rights : FileSystemRights * 
        accessControlType : AccessControlType -> bool 

```


#### Parameters
&nbsp;<dl><dt>directoryPath</dt><dd>Type: System.String<br />The directory path.</dd><dt>rights</dt><dd>Type: System.Security.AccessControl.FileSystemRights<br />The user-rights.</dd><dt>accessControlType</dt><dd>Type: System.Security.AccessControl.AccessControlType<br />The access control type, determines whether to check for allowed user-rights or denied user-rights.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the directory contains the user-rights; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim hasRights As Boolean = HasRights("C:\Directory\",
                                     FileSystemRights.Read Or FileSystemRights.Write,
                                     AccessControlType.Allow)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DirectoryUtil_HasRights">HasRights Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />