# IniSection Constructor (String, IniKeyCollection)
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IniSection(
	string name,
	IniKeyCollection keys
)
```

**VB**<br />
``` VB
Public Sub New ( 
	name As String,
	keys As IniKeyCollection
)
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim keys As IniKeyCollection

Dim instance As New IniSection(name, keys)
```

**C++**<br />
``` C++
public:
IniSection(
	String^ name, 
	IniKeyCollection^ keys
)
```

**F#**<br />
``` F#
new : 
        name : string * 
        keys : IniKeyCollection -> IniSection
```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The section name.</dd><dt>keys</dt><dd>Type: <a href="T_DevCase_Core_Application_Data_IniKeyCollection">DevCase.Core.Application.Data.IniKeyCollection</a><br />The section keys.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>name</td></tr><tr><td>ArgumentException</td><td>The section name cannot contain the '[' or ']' symbols because it identifies a section.,name</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniSection">IniSection Class</a><br /><a href="Overload_DevCase_Core_Application_Data_IniSection__ctor">IniSection Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />