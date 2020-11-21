# FileUtil.CreateSymbolicLink Method (String, DirectoryInfo)
 

Creates a symbolic link of the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CreateSymbolicLink(
	string srcFilePath,
	DirectoryInfo dstDirPath
)
```

**VB**<br />
``` VB
Public Shared Sub CreateSymbolicLink ( 
	srcFilePath As String,
	dstDirPath As DirectoryInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim srcFilePath As String
Dim dstDirPath As DirectoryInfoFileUtil.CreateSymbolicLink(srcFilePath, 
	dstDirPath)
```

**C++**<br />
``` C++
public:
static void CreateSymbolicLink(
	String^ srcFilePath, 
	DirectoryInfo^ dstDirPath
)
```

**F#**<br />
``` F#
static member CreateSymbolicLink : 
        srcFilePath : string * 
        dstDirPath : DirectoryInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>srcFilePath</dt><dd>Type: System.String<br />The source file path.</dd><dt>dstDirPath</dt><dd>Type: System.IO.DirectoryInfo<br />The destination directory where to create the symbolic link.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_CreateSymbolicLink">CreateSymbolicLink Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />