# BBCodeDocument.Load Method (String)
 

Loads a string of BBCode as a BBCodeDocument object

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static BBCodeDocument Load(
	string bbCode
)
```

**VB**<br />
``` VB
Public Shared Function Load ( 
	bbCode As String
) As BBCodeDocument
```

**VB Usage**<br />
``` VB Usage
Dim bbCode As String
Dim returnValue As BBCodeDocument

returnValue = BBCodeDocument.Load(bbCode)
```

**C++**<br />
``` C++
public:
static BBCodeDocument^ Load(
	String^ bbCode
)
```

**F#**<br />
``` F#
static member Load : 
        bbCode : string -> BBCodeDocument 

```


#### Parameters
&nbsp;<dl><dt>bbCode</dt><dd>Type: System.String<br />A string of BBCode text.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_NET_BBCodeDocument">BBCodeDocument</a><br />The DOM representation of the text.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_BBCodeDocument">BBCodeDocument Class</a><br /><a href="Overload_DevCase_Core_NET_BBCodeDocument_Load">Load Overload</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />