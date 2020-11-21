# IniKeyCollection.Add Method (IniKey)
 

Adds a <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> to the end of the <a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Add(
	IniKey key
)
```

**VB**<br />
``` VB
Public Sub Add ( 
	key As IniKey
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniKeyCollection
Dim key As IniKey

instance.Add(key)
```

**C++**<br />
``` C++
public:
void Add(
	IniKey^ key
)
```

**F#**<br />
``` F#
member Add : 
        key : IniKey -> unit 

```


#### Parameters
&nbsp;<dl><dt>key</dt><dd>Type: <a href="T_DevCase_Core_Application_Data_IniKey">DevCase.Core.Application.Data.IniKey</a><br />The key to add.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Section already exists.;section</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection Class</a><br /><a href="Overload_DevCase_Core_Application_Data_IniKeyCollection_Add">Add Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />