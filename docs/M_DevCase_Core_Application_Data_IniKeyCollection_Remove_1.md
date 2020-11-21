# IniKeyCollection.Remove Method (String)
 

Removes a <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> from the <a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Remove(
	string keyName
)
```

**VB**<br />
``` VB
Public Sub Remove ( 
	keyName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniKeyCollection
Dim keyName As String

instance.Remove(keyName)
```

**C++**<br />
``` C++
public:
void Remove(
	String^ keyName
)
```

**F#**<br />
``` F#
member Remove : 
        keyName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>keyName</dt><dd>Type: System.String<br />The key to remove.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Key doesn't exists.;keyName</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection Class</a><br /><a href="Overload_DevCase_Core_Application_Data_IniKeyCollection_Remove">Remove Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />