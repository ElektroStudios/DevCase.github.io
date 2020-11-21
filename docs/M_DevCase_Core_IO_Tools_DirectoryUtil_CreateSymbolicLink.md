# DirectoryUtil.CreateSymbolicLink Method (DirectoryInfo, DirectoryInfo)
 

Creates a symbolic link of the specified directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CreateSymbolicLink(
	DirectoryInfo srcDir,
	DirectoryInfo dstDir
)
```

**VB**<br />
``` VB
Public Shared Sub CreateSymbolicLink ( 
	srcDir As DirectoryInfo,
	dstDir As DirectoryInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim srcDir As DirectoryInfo
Dim dstDir As DirectoryInfoDirectoryUtil.CreateSymbolicLink(srcDir, 
	dstDir)
```

**C++**<br />
``` C++
public:
static void CreateSymbolicLink(
	DirectoryInfo^ srcDir, 
	DirectoryInfo^ dstDir
)
```

**F#**<br />
``` F#
static member CreateSymbolicLink : 
        srcDir : DirectoryInfo * 
        dstDir : DirectoryInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>srcDir</dt><dd>Type: System.IO.DirectoryInfo<br />The source directory.</dd><dt>dstDir</dt><dd>Type: System.IO.DirectoryInfo<br />The destination directory where to create the symbolic link.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DirectoryUtil_CreateSymbolicLink">CreateSymbolicLink Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />