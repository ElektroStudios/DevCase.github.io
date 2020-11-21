# FileUtil.HasAttributes Method (String, FileAttributes)
 

Gets a value indicating whether a file contains the specified file-attribute(s).

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool HasAttributes(
	string filepath,
	FileAttributes attributes
)
```

**VB**<br />
``` VB
Public Shared Function HasAttributes ( 
	filepath As String,
	attributes As FileAttributes
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim attributes As FileAttributes
Dim returnValue As Boolean

returnValue = FileUtil.HasAttributes(filepath, 
	attributes)
```

**C++**<br />
``` C++
public:
static bool HasAttributes(
	String^ filepath, 
	FileAttributes attributes
)
```

**F#**<br />
``` F#
static member HasAttributes : 
        filepath : string * 
        attributes : FileAttributes -> bool 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The filepath.</dd><dt>attributes</dt><dd>Type: System.IO.FileAttributes<br />The file attribute(s).</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if file contains the file-attribute(s), `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim hasAttribute As Boolean = HasAttributes("C:\File.ext", FileAttributes.Hidden Or FileAttributes.ReadOnly)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_HasAttributes">HasAttributes Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />