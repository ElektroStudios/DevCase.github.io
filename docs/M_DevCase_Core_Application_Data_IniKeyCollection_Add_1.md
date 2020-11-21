# IniKeyCollection.Add Method (String, String, String)
 

Adds a <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> to the end of the <a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Add(
	string name,
	string value,
	string comment = ""
)
```

**VB**<br />
``` VB
Public Sub Add ( 
	name As String,
	value As String,
	Optional comment As String = ""
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniKeyCollection
Dim name As String
Dim value As String
Dim comment As String

instance.Add(name, value, comment)
```

**C++**<br />
``` C++
public:
void Add(
	String^ name, 
	String^ value, 
	String^ comment = L""
)
```

**F#**<br />
``` F#
member Add : 
        name : string * 
        value : string * 
        ?comment : string 
(* Defaults:
        let _comment = defaultArg comment ""
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the key to add.</dd><dt>value</dt><dd>Type: System.String<br />The value.</dd><dt>comment (Optional)</dt><dd>Type: System.String<br />An optional comment-line.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Key already exists.;section</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection Class</a><br /><a href="Overload_DevCase_Core_Application_Data_IniKeyCollection_Add">Add Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />