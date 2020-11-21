# FileUtil.RemoveAttributes Method (String, FileAttributes)
 

Removes file-attribute(s) from the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RemoveAttributes(
	string filepath,
	FileAttributes attributes
)
```

**VB**<br />
``` VB
Public Shared Sub RemoveAttributes ( 
	filepath As String,
	attributes As FileAttributes
)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim attributes As FileAttributesFileUtil.RemoveAttributes(filepath, 
	attributes)
```

**C++**<br />
``` C++
public:
static void RemoveAttributes(
	String^ filepath, 
	FileAttributes attributes
)
```

**F#**<br />
``` F#
static member RemoveAttributes : 
        filepath : string * 
        attributes : FileAttributes -> unit 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The filepath.</dd><dt>attributes</dt><dd>Type: System.IO.FileAttributes<br />The file attribute(s) to remove.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
RemoveAttributes("C:\File.ext", FileAttributes.Hidden Or FileAttributes.ReadOnly)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_RemoveAttributes">RemoveAttributes Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />