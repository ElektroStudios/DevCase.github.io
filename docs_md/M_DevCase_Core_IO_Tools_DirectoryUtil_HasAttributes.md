# DirectoryUtil.HasAttributes Method 
 

Gets a value indicating whether a directory contains the specified directory-attribute(s).

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool HasAttributes(
	string directoryPath,
	FileAttributes attributes
)
```

**VB**<br />
``` VB
Public Shared Function HasAttributes ( 
	directoryPath As String,
	attributes As FileAttributes
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim directoryPath As String
Dim attributes As FileAttributes
Dim returnValue As Boolean

returnValue = DirectoryUtil.HasAttributes(directoryPath, 
	attributes)
```

**C++**<br />
``` C++
public:
static bool HasAttributes(
	String^ directoryPath, 
	FileAttributes attributes
)
```

**F#**<br />
``` F#
static member HasAttributes : 
        directoryPath : string * 
        attributes : FileAttributes -> bool 

```


#### Parameters
&nbsp;<dl><dt>directoryPath</dt><dd>Type: System.String<br />The directory path.</dd><dt>attributes</dt><dd>Type: System.IO.FileAttributes<br />The directory attribute(s).</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if file contains the directory-attribute(s), `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim hasAttribute As Boolean = HasAttributesAttributes("C:\Directory\", FileAttributes.Hidden Or FileAttributes.ReadOnly)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />