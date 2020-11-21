# FileTypeMatch Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_FileTypeMatch">FileTypeMatch</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FileTypeMatch(
	byte[] fileHeader,
	FileType filetype,
	int signatureMatchCount
)
```

**VB**<br />
``` VB
Public Sub New ( 
	fileHeader As Byte(),
	filetype As FileType,
	signatureMatchCount As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim fileHeader As Byte()
Dim filetype As FileType
Dim signatureMatchCount As Integer

Dim instance As New FileTypeMatch(fileHeader, 
	filetype, signatureMatchCount)
```

**C++**<br />
``` C++
public:
FileTypeMatch(
	array<unsigned char>^ fileHeader, 
	FileType^ filetype, 
	int signatureMatchCount
)
```

**F#**<br />
``` F#
new : 
        fileHeader : byte[] * 
        filetype : FileType * 
        signatureMatchCount : int -> FileTypeMatch
```


#### Parameters
&nbsp;<dl><dt>fileHeader</dt><dd>Type: System.Byte[]<br />The source file header.</dd><dt>filetype</dt><dd>Type: <a href="T_DevCase_Core_IO_FileType">DevCase.Core.IO.FileType</a><br />The <a href="T_DevCase_Core_IO_FileType">FileType</a> that has been matched in the source file header.</dd><dt>signatureMatchCount</dt><dd>Type: System.Int32<br />The amount of signatures that were found in the source file header.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>signatureMatchCount;Value must be less or equal than signatures count.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileTypeMatch">FileTypeMatch Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />