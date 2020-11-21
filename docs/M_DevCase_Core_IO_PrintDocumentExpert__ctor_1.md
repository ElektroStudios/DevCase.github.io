# PrintDocumentExpert Constructor (String, Encoding)
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_PrintDocumentExpert">PrintDocumentExpert</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PrintDocumentExpert(
	string filepath,
	Encoding encoding
)
```

**VB**<br />
``` VB
Public Sub New ( 
	filepath As String,
	encoding As Encoding
)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim encoding As Encoding

Dim instance As New PrintDocumentExpert(filepath, 
	encoding)
```

**C++**<br />
``` C++
public:
PrintDocumentExpert(
	String^ filepath, 
	Encoding^ encoding
)
```

**F#**<br />
``` F#
new : 
        filepath : string * 
        encoding : Encoding -> PrintDocumentExpert
```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The document file path.</dd><dt>encoding</dt><dd>Type: System.Text.Encoding<br />The text encoding.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_PrintDocumentExpert">PrintDocumentExpert Class</a><br /><a href="Overload_DevCase_Core_IO_PrintDocumentExpert__ctor">PrintDocumentExpert Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />