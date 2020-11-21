# IniKey Constructor (String, String, String)
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IniKey(
	string name,
	string value,
	string comment = ""
)
```

**VB**<br />
``` VB
Public Sub New ( 
	name As String,
	value As String,
	Optional comment As String = ""
)
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim value As String
Dim comment As String

Dim instance As New IniKey(name, value, 
	comment)
```

**C++**<br />
``` C++
public:
IniKey(
	String^ name, 
	String^ value, 
	String^ comment = L""
)
```

**F#**<br />
``` F#
new : 
        name : string * 
        value : string * 
        ?comment : string 
(* Defaults:
        let _comment = defaultArg comment ""
*)
-> IniKey
```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The key name.</dd><dt>value</dt><dd>Type: System.String<br />The key value.</dd><dt>comment (Optional)</dt><dd>Type: System.String<br />The key commentary-line.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>name</td></tr><tr><td>ArgumentException</td><td>The key name cannot contain the ';' symbol because it identifies a commentary line.,name or The key name cannot contain the '=' symbol because it delimits the name from the value.,name</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniKey">IniKey Class</a><br /><a href="Overload_DevCase_Core_Application_Data_IniKey__ctor">IniKey Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />