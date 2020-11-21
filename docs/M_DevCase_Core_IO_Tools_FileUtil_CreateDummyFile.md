# FileUtil.CreateDummyFile Method (String)
 

Creates a dummy (zero-byte filled) file of zero size.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CreateDummyFile(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Sub CreateDummyFile ( 
	filepath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As StringFileUtil.CreateDummyFile(filepath)
```

**C++**<br />
``` C++
public:
static void CreateDummyFile(
	String^ filepath
)
```

**F#**<br />
``` F#
static member CreateDummyFile : 
        filepath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The target filepath.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>IOException</td><td>Target file already exists.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
CreateDummyFile("C:\DummyFile.tmp"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_CreateDummyFile">CreateDummyFile Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />