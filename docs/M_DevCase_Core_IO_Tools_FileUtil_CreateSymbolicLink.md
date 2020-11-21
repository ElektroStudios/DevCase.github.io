# FileUtil.CreateSymbolicLink Method (FileInfo, DirectoryInfo)
 

Creates a symbolic link of the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CreateSymbolicLink(
	FileInfo srcFile,
	DirectoryInfo dstDir
)
```

**VB**<br />
``` VB
Public Shared Sub CreateSymbolicLink ( 
	srcFile As FileInfo,
	dstDir As DirectoryInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim srcFile As FileInfo
Dim dstDir As DirectoryInfoFileUtil.CreateSymbolicLink(srcFile, 
	dstDir)
```

**C++**<br />
``` C++
public:
static void CreateSymbolicLink(
	FileInfo^ srcFile, 
	DirectoryInfo^ dstDir
)
```

**F#**<br />
``` F#
static member CreateSymbolicLink : 
        srcFile : FileInfo * 
        dstDir : DirectoryInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>srcFile</dt><dd>Type: System.IO.FileInfo<br />The source file.</dd><dt>dstDir</dt><dd>Type: System.IO.DirectoryInfo<br />The destination directory where to create the symbolic link.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_CreateSymbolicLink">CreateSymbolicLink Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />