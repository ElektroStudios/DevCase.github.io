# DirectoryUtil.IsDirectory Method 
 

Determines whether the specified path points to a existing directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsDirectory(
	string directoryPath
)
```

**VB**<br />
``` VB
Public Shared Function IsDirectory ( 
	directoryPath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim directoryPath As String
Dim returnValue As Boolean

returnValue = DirectoryUtil.IsDirectory(directoryPath)
```

**C++**<br />
``` C++
public:
static bool IsDirectory(
	String^ directoryPath
)
```

**F#**<br />
``` F#
static member IsDirectory : 
        directoryPath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>directoryPath</dt><dd>Type: System.String<br />The source directory path.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified path points to a existing directory; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />