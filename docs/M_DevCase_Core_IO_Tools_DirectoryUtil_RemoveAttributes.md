# DirectoryUtil.RemoveAttributes Method 
 

Removes directory-attribute(s) from the specified directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RemoveAttributes(
	string directoryPath,
	FileAttributes attributes
)
```

**VB**<br />
``` VB
Public Shared Sub RemoveAttributes ( 
	directoryPath As String,
	attributes As FileAttributes
)
```

**VB Usage**<br />
``` VB Usage
Dim directoryPath As String
Dim attributes As FileAttributesDirectoryUtil.RemoveAttributes(directoryPath, 
	attributes)
```

**C++**<br />
``` C++
public:
static void RemoveAttributes(
	String^ directoryPath, 
	FileAttributes attributes
)
```

**F#**<br />
``` F#
static member RemoveAttributes : 
        directoryPath : string * 
        attributes : FileAttributes -> unit 

```


#### Parameters
&nbsp;<dl><dt>directoryPath</dt><dd>Type: System.String<br />The directory path.</dd><dt>attributes</dt><dd>Type: System.IO.FileAttributes<br />The directory attribute(s) to remove.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
RemoveAttributes("C:\Directory\", FileAttributes.Hidden Or FileAttributes.ReadOnly)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />