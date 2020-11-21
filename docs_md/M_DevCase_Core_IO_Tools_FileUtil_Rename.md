# FileUtil.Rename Method (FileInfo, String, String)
 

Renames a file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Rename(
	FileInfo file,
	string targetFileName,
	string targetFileExt = ""
)
```

**VB**<br />
``` VB
Public Shared Sub Rename ( 
	file As FileInfo,
	targetFileName As String,
	Optional targetFileExt As String = ""
)
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim targetFileName As String
Dim targetFileExt As StringFileUtil.Rename(file, targetFileName, 
	targetFileExt)
```

**C++**<br />
``` C++
public:
static void Rename(
	FileInfo^ file, 
	String^ targetFileName, 
	String^ targetFileExt = L""
)
```

**F#**<br />
``` F#
static member Rename : 
        file : FileInfo * 
        targetFileName : string * 
        ?targetFileExt : string 
(* Defaults:
        let _targetFileExt = defaultArg targetFileExt ""
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The source file.</dd><dt>targetFileName</dt><dd>Type: System.String<br />The target file name (without file extension).</dd><dt>targetFileExt (Optional)</dt><dd>Type: System.String<br />The target file extension. 

 If this parameter is String, the same file extension is assumed.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Source file not found.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Rename(New FileInfo("C:\File.ext"), "new filename", ".ext")
Rename(New FileInfo("C:\File.ext"), "new filename", "") ' Preserve file extenstion.
```


## Examples
This is a code example that renames the file extension of all files in the specified directory. 
**VB**<br />
``` VB
Dim dInfo As New DirectoryInfo("C:\Directory\")
dInfo.EnumerateFiles("*.jpg", SearchOption.TopDirectoryOnly).ToList.
    ForEach(Sub(fInfo As FileInfo)
                Rename(fInfo, fInfo.Name, ".png")
            End Sub)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_Rename">Rename Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />