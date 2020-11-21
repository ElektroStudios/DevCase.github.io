# FileUtil.AddAttributes Method (String, FileAttributes)
 

Adss file-attribute(s) to the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void AddAttributes(
	string filepath,
	FileAttributes attributes
)
```

**VB**<br />
``` VB
Public Shared Sub AddAttributes ( 
	filepath As String,
	attributes As FileAttributes
)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim attributes As FileAttributesFileUtil.AddAttributes(filepath, attributes)
```

**C++**<br />
``` C++
public:
static void AddAttributes(
	String^ filepath, 
	FileAttributes attributes
)
```

**F#**<br />
``` F#
static member AddAttributes : 
        filepath : string * 
        attributes : FileAttributes -> unit 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The filepath.</dd><dt>attributes</dt><dd>Type: System.IO.FileAttributes<br />The file attribute(s) to add.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
AddAttributes("C:\File.ext", FileAttributes.Hidden Or FileAttributes.ReadOnly)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_AddAttributes">AddAttributes Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />