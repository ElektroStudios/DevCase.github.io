# IniKeyCollection.AddRange Method (IniKey[])
 

Adds the specified keys to the end of the <a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void AddRange(
	IniKey[] keys
)
```

**VB**<br />
``` VB
Public Sub AddRange ( 
	keys As IniKey()
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniKeyCollection
Dim keys As IniKey()

instance.AddRange(keys)
```

**C++**<br />
``` C++
public:
void AddRange(
	array<IniKey^>^ keys
)
```

**F#**<br />
``` F#
member AddRange : 
        keys : IniKey[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>keys</dt><dd>Type: <a href="T_DevCase_Core_Application_Data_IniKey">DevCase.Core.Application.Data.IniKey</a>[]<br />The keys to add.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Key already exists.;section</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection Class</a><br /><a href="Overload_DevCase_Core_Application_Data_IniKeyCollection_AddRange">AddRange Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />