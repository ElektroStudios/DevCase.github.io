# DirectoryUtil.Rename Method 
 

Renames a directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Rename(
	string sourceDirPath,
	string targetDirName
)
```

**VB**<br />
``` VB
Public Shared Sub Rename ( 
	sourceDirPath As String,
	targetDirName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim sourceDirPath As String
Dim targetDirName As StringDirectoryUtil.Rename(sourceDirPath, targetDirName)
```

**C++**<br />
``` C++
public:
static void Rename(
	String^ sourceDirPath, 
	String^ targetDirName
)
```

**F#**<br />
``` F#
static member Rename : 
        sourceDirPath : string * 
        targetDirName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>sourceDirPath</dt><dd>Type: System.String<br />The source directory path.</dd><dt>targetDirName</dt><dd>Type: System.String<br />The target directory name.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>DirectoryNotFoundException</td><td>Source directory not found.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Rename("C:\Directory\", "new directory name")
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />