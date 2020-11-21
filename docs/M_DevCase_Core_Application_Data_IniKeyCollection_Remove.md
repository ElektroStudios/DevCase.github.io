# IniKeyCollection.Remove Method (IniKey)
 

Removes a <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> from the <a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Remove(
	IniKey key
)
```

**VB**<br />
``` VB
Public Sub Remove ( 
	key As IniKey
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniKeyCollection
Dim key As IniKey

instance.Remove(key)
```

**C++**<br />
``` C++
public:
void Remove(
	IniKey^ key
)
```

**F#**<br />
``` F#
member Remove : 
        key : IniKey -> unit 

```


#### Parameters
&nbsp;<dl><dt>key</dt><dd>Type: <a href="T_DevCase_Core_Application_Data_IniKey">DevCase.Core.Application.Data.IniKey</a><br />The key to remove.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Key doesn't exists.;key</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection Class</a><br /><a href="Overload_DevCase_Core_Application_Data_IniKeyCollection_Remove">Remove Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />