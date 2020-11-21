# DirectoryUtil.CreateSymbolicLink Method (String, DirectoryInfo)
 

Creates a symbolic link of the specified directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CreateSymbolicLink(
	string srcDirPath,
	DirectoryInfo dstDirPath
)
```

**VB**<br />
``` VB
Public Shared Sub CreateSymbolicLink ( 
	srcDirPath As String,
	dstDirPath As DirectoryInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim srcDirPath As String
Dim dstDirPath As DirectoryInfoDirectoryUtil.CreateSymbolicLink(srcDirPath, 
	dstDirPath)
```

**C++**<br />
``` C++
public:
static void CreateSymbolicLink(
	String^ srcDirPath, 
	DirectoryInfo^ dstDirPath
)
```

**F#**<br />
``` F#
static member CreateSymbolicLink : 
        srcDirPath : string * 
        dstDirPath : DirectoryInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>srcDirPath</dt><dd>Type: System.String<br />The source directory path.</dd><dt>dstDirPath</dt><dd>Type: System.IO.DirectoryInfo<br />The destination directory where to create the symbolic link.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DirectoryUtil_CreateSymbolicLink">CreateSymbolicLink Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />