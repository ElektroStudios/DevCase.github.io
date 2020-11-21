# FileUtil.Lock Method (FileInfo, FileShare)
 

Locks read/write access to the specified file for other applications (during the lifetime of the current application). 

 To unlock the file, just dispose the returned FileStream object.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static FileStream Lock(
	FileInfo file,
	FileShare fileShare = FileShare.Read
)
```

**VB**<br />
``` VB
Public Shared Function Lock ( 
	file As FileInfo,
	Optional fileShare As FileShare = FileShare.Read
) As FileStream
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim fileShare As FileShare
Dim returnValue As FileStream

returnValue = FileUtil.Lock(file, fileShare)
```

**C++**<br />
``` C++
public:
static FileStream^ Lock(
	FileInfo^ file, 
	FileShare fileShare = FileShare::Read
)
```

**F#**<br />
``` F#
static member Lock : 
        file : FileInfo * 
        ?fileShare : FileShare 
(* Defaults:
        let _fileShare = defaultArg fileShare FileShare.Read
*)
-> FileStream 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The source file.</dd><dt>fileShare (Optional)</dt><dd>Type: System.IO.FileShare<br />The type of access that other applications will have to this file.</dd></dl>

#### Return Value
Type: FileStream<br />A FileStream object that represents the file stream.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\File.ext")
Using fs As FileStream = Lock(file, FileShare.Read)
 ' ...
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_Lock">Lock Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />