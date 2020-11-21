# Resource(*T*) Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_Data_Resource_1">Resource(T)</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Resource(
	string name,
	T data,
	string comment
)
```

**VB**<br />
``` VB
Public Sub New ( 
	name As String,
	data As T,
	comment As String
)
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim data As T
Dim comment As String

Dim instance As New Resource(name, data, 
	comment)
```

**C++**<br />
``` C++
public:
Resource(
	String^ name, 
	T data, 
	String^ comment
)
```

**F#**<br />
``` F#
new : 
        name : string * 
        data : 'T * 
        comment : string -> Resource
```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The resource name.</dd><dt>data</dt><dd>Type: <a href="T_DevCase_Core_Application_Data_Resource_1">*T*</a><br />The resource data.</dd><dt>comment</dt><dd>Type: System.String<br />The resource comment.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Resource_1">Resource(T) Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />