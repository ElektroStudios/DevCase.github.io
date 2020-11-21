# FileUtil.CreateDummyFile Method (String, Int64)
 

Creates a dummy (zero-byte filled) file of the specified filesize.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CreateDummyFile(
	string filepath,
	long filesize
)
```

**VB**<br />
``` VB
Public Shared Sub CreateDummyFile ( 
	filepath As String,
	filesize As Long
)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim filesize As Long

FileUtil.CreateDummyFile(filepath, filesize)
```

**C++**<br />
``` C++
public:
static void CreateDummyFile(
	String^ filepath, 
	long long filesize
)
```

**F#**<br />
``` F#
static member CreateDummyFile : 
        filepath : string * 
        filesize : int64 -> unit 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The target filepath.</dd><dt>filesize</dt><dd>Type: System.Int64<br />The filesize, in Bytes.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>IOException</td><td>Target file already exists.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
CreateDummyFile("C:\DummyFile.tmp", CLng(Math.Pow(1024L, 3L))) ' 1 GB filesize.
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_CreateDummyFile">CreateDummyFile Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />