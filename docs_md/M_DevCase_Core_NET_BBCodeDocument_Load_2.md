# BBCodeDocument.Load Method (String, Boolean, IEnumerable(String))
 

Loads a string of BBCode as a BBCodeDocument object

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static BBCodeDocument Load(
	string bbCode,
	bool throwOnError,
	IEnumerable<string> singularTags
)
```

**VB**<br />
``` VB
Public Shared Function Load ( 
	bbCode As String,
	throwOnError As Boolean,
	singularTags As IEnumerable(Of String)
) As BBCodeDocument
```

**VB Usage**<br />
``` VB Usage
Dim bbCode As String
Dim throwOnError As Boolean
Dim singularTags As IEnumerable(Of String)
Dim returnValue As BBCodeDocument

returnValue = BBCodeDocument.Load(bbCode, throwOnError, 
	singularTags)
```

**C++**<br />
``` C++
public:
static BBCodeDocument^ Load(
	String^ bbCode, 
	bool throwOnError, 
	IEnumerable<String^>^ singularTags
)
```

**F#**<br />
``` F#
static member Load : 
        bbCode : string * 
        throwOnError : bool * 
        singularTags : IEnumerable<string> -> BBCodeDocument 

```


#### Parameters
&nbsp;<dl><dt>bbCode</dt><dd>Type: System.String<br />A string of BBCode text.</dd><dt>throwOnError</dt><dd>Type: System.Boolean<br />Whether to throw an exception on parse error. If false, the error is ignored.</dd><dt>singularTags</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />A list of tags which should be considered singular by the parser. 

 Singular tags are self closing and may not have children.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_NET_BBCodeDocument">BBCodeDocument</a><br />The DOM representation of the text.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_BBCodeDocument">BBCodeDocument Class</a><br /><a href="Overload_DevCase_Core_NET_BBCodeDocument_Load">Load Overload</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />