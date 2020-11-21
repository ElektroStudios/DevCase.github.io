# FileType Constructor (FileSignature, String, String, String)
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_FileType">FileType</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FileType(
	FileSignature signature,
	string name,
	string extension,
	string mime
)
```

**VB**<br />
``` VB
Public Sub New ( 
	signature As FileSignature,
	name As String,
	extension As String,
	mime As String
)
```

**VB Usage**<br />
``` VB Usage
Dim signature As FileSignature
Dim name As String
Dim extension As String
Dim mime As String

Dim instance As New FileType(signature, 
	name, extension, mime)
```

**C++**<br />
``` C++
public:
FileType(
	FileSignature^ signature, 
	String^ name, 
	String^ extension, 
	String^ mime
)
```

**F#**<br />
``` F#
new : 
        signature : FileSignature * 
        name : string * 
        extension : string * 
        mime : string -> FileType
```


#### Parameters
&nbsp;<dl><dt>signature</dt><dd>Type: <a href="T_DevCase_Core_IO_FileSignature">DevCase.Core.IO.FileSignature</a><br />The <a href="T_DevCase_Core_IO_FileSignature">FileSignature</a> used to identify the format of the filetype.</dd><dt>name</dt><dd>Type: System.String<br />The complete filetype name.</dd><dt>extension</dt><dd>Type: System.String<br />The filetype extension (e.g: exe, jpg, zip)</dd><dt>mime</dt><dd>Type: System.String<br />The `MIME` name that identifies the content type of the filetype.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileType">FileType Class</a><br /><a href="Overload_DevCase_Core_IO_FileType__ctor">FileType Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />