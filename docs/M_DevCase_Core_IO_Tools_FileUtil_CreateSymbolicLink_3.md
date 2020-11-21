# FileUtil.CreateSymbolicLink Method (String, String)
 

Creates a symbolic link of the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CreateSymbolicLink(
	string srcFilePath,
	string dstDirPath
)
```

**VB**<br />
``` VB
Public Shared Sub CreateSymbolicLink ( 
	srcFilePath As String,
	dstDirPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim srcFilePath As String
Dim dstDirPath As StringFileUtil.CreateSymbolicLink(srcFilePath, 
	dstDirPath)
```

**C++**<br />
``` C++
public:
static void CreateSymbolicLink(
	String^ srcFilePath, 
	String^ dstDirPath
)
```

**F#**<br />
``` F#
static member CreateSymbolicLink : 
        srcFilePath : string * 
        dstDirPath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>srcFilePath</dt><dd>Type: System.String<br />The source file path.</dd><dt>dstDirPath</dt><dd>Type: System.String<br />The destination directory path where to create the symbolic link.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td /></tr><tr><td>IOException</td><td /></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_CreateSymbolicLink">CreateSymbolicLink Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />