# FileSignature.Inequality Operator 
 

Implements the operator <>

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool operator !=(
	FileSignature signatureA,
	FileSignature signatureB
)
```

**VB**<br />
``` VB
Public Shared Operator <> ( 
	signatureA As FileSignature,
	signatureB As FileSignature
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim signatureA As FileSignature
Dim signatureB As FileSignature
Dim returnValue As Boolean

returnValue = (signatureA <> signatureB)
```

**C++**<br />
``` C++
public:
static bool operator !=(
	FileSignature^ signatureA, 
	FileSignature^ signatureB
)
```

**F#**<br />
``` F#
static let inline (<>)
        signatureA : FileSignature * 
        signatureB : FileSignature  : bool
```


#### Parameters
&nbsp;<dl><dt>signatureA</dt><dd>Type: <a href="T_DevCase_Core_IO_FileSignature">DevCase.Core.IO.FileSignature</a><br />The first <a href="T_DevCase_Core_IO_FileSignature">FileSignature</a> to evaluate.</dd><dt>signatureB</dt><dd>Type: <a href="T_DevCase_Core_IO_FileSignature">DevCase.Core.IO.FileSignature</a><br />The second <a href="T_DevCase_Core_IO_FileSignature">FileSignature</a> to evaluate.</dd></dl>

#### Return Value
Type: Boolean<br />The result of the operator.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileSignature">FileSignature Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />