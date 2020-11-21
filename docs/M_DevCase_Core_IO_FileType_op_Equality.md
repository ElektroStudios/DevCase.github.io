# FileType.Equality Operator 
 

Implements the operator =

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool operator ==(
	FileType filetypeA,
	FileType filetypeB
)
```

**VB**<br />
``` VB
Public Shared Operator = ( 
	filetypeA As FileType,
	filetypeB As FileType
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim filetypeA As FileType
Dim filetypeB As FileType
Dim returnValue As Boolean

returnValue = (filetypeA = filetypeB)
```

**C++**<br />
``` C++
public:
static bool operator ==(
	FileType^ filetypeA, 
	FileType^ filetypeB
)
```

**F#**<br />
``` F#
static let inline (=)
        filetypeA : FileType * 
        filetypeB : FileType  : bool
```


#### Parameters
&nbsp;<dl><dt>filetypeA</dt><dd>Type: <a href="T_DevCase_Core_IO_FileType">DevCase.Core.IO.FileType</a><br />The first <a href="T_DevCase_Core_IO_FileType">FileType</a> to evaluate.</dd><dt>filetypeB</dt><dd>Type: <a href="T_DevCase_Core_IO_FileType">DevCase.Core.IO.FileType</a><br />The second <a href="T_DevCase_Core_IO_FileType">FileType</a> to evaluate.</dd></dl>

#### Return Value
Type: Boolean<br />The result of the operator.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileType">FileType Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />