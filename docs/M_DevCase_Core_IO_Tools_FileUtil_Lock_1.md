# FileUtil.Lock Method (String, FileShare)
 

Locks read/write access to the specified file for other applications (during the lifetime of the current application). 

 To unlock the file, just dispose the returned FileStream object.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static FileStream Lock(
	string filepath,
	FileShare fileShare = FileShare.Read
)
```

**VB**<br />
``` VB
Public Shared Function Lock ( 
	filepath As String,
	Optional fileShare As FileShare = FileShare.Read
) As FileStream
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim fileShare As FileShare
Dim returnValue As FileStream

returnValue = FileUtil.Lock(filepath, 
	fileShare)
```

**C++**<br />
``` C++
public:
static FileStream^ Lock(
	String^ filepath, 
	FileShare fileShare = FileShare::Read
)
```

**F#**<br />
``` F#
static member Lock : 
        filepath : string * 
        ?fileShare : FileShare 
(* Defaults:
        let _fileShare = defaultArg fileShare FileShare.Read
*)
-> FileStream 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The file path.</dd><dt>fileShare (Optional)</dt><dd>Type: System.IO.FileShare<br />The type of access that other applications will have to this file.</dd></dl>

#### Return Value
Type: FileStream<br />A FileStream object that represents the file stream.

## Examples
This is a code example. 
**VB**<br />
``` VB
Using fs As FileStream = Lock("C:\File.txt", FileShare.Read)
 ' ...
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_Lock">Lock Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />