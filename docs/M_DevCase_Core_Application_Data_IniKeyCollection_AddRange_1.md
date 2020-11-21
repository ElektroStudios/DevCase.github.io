# IniKeyCollection.AddRange Method (String[])
 

Adds the specified keys to the end of the <a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void AddRange(
	string[] keyNames
)
```

**VB**<br />
``` VB
Public Sub AddRange ( 
	keyNames As String()
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniKeyCollection
Dim keyNames As String()

instance.AddRange(keyNames)
```

**C++**<br />
``` C++
public:
void AddRange(
	array<String^>^ keyNames
)
```

**F#**<br />
``` F#
member AddRange : 
        keyNames : string[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>keyNames</dt><dd>Type: System.String[]<br />The names of the keys to add.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Section already exists.;section</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection Class</a><br /><a href="Overload_DevCase_Core_Application_Data_IniKeyCollection_AddRange">AddRange Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />