# EasyXmlTextWriter Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Xml_EasyXmlTextWriter">EasyXmlTextWriter</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Xml">DevCase.Core.Xml</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public EasyXmlTextWriter(
	string filename,
	Encoding enc
)
```

**VB**<br />
``` VB
Public Sub New ( 
	filename As String,
	enc As Encoding
)
```

**VB Usage**<br />
``` VB Usage
Dim filename As String
Dim enc As Encoding

Dim instance As New EasyXmlTextWriter(filename, 
	enc)
```

**C++**<br />
``` C++
public:
EasyXmlTextWriter(
	String^ filename, 
	Encoding^ enc
)
```

**F#**<br />
``` F#
new : 
        filename : string * 
        enc : Encoding -> EasyXmlTextWriter
```


#### Parameters
&nbsp;<dl><dt>filename</dt><dd>Type: System.String<br />The filename to write to. 

 If the file exists, it truncates it and overwrites it with the new content.</dd><dt>enc</dt><dd>Type: System.Text.Encoding<br />The encoding to generate. 

 If encoding is null it writes the file out as UTF-8, and omits the encoding attribute from the ProcessingInstruction.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Xml_EasyXmlTextWriter">EasyXmlTextWriter Class</a><br /><a href="N_DevCase_Core_Xml">DevCase.Core.Xml Namespace</a><br />