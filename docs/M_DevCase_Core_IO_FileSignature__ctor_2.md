# FileSignature Constructor (Nullable(Byte)[], Int32, String)
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_FileSignature">FileSignature</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FileSignature(
	Nullable<byte>[] signature,
	int offset,
	string description
)
```

**VB**<br />
``` VB
Public Sub New ( 
	signature As Nullable(Of Byte)(),
	offset As Integer,
	description As String
)
```

**VB Usage**<br />
``` VB Usage
Dim signature As Nullable(Of Byte)()
Dim offset As Integer
Dim description As String

Dim instance As New FileSignature(signature, 
	offset, description)
```

**C++**<br />
``` C++
public:
FileSignature(
	array<Nullable<unsigned char>>^ signature, 
	int offset, 
	String^ description
)
```

**F#**<br />
``` F#
new : 
        signature : Nullable<byte>[] * 
        offset : int * 
        description : string -> FileSignature
```


#### Parameters
&nbsp;<dl><dt>signature</dt><dd>Type: System.Nullable(Byte)[]<br />The file signature.</dd><dt>offset</dt><dd>Type: System.Int32<br />The offset position of the signature.</dd><dt>description</dt><dd>Type: System.String<br />A description for this signature. (e.g. the filetype extension or any other comment)</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileSignature">FileSignature Class</a><br /><a href="Overload_DevCase_Core_IO_FileSignature__ctor">FileSignature Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />