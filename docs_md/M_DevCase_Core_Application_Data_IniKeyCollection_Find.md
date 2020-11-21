# IniKeyCollection.Find Method 
 

Searches for an <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> that matches the specified key name, and returns the first occurrence within the entire <a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IniKey Find(
	string keyName
)
```

**VB**<br />
``` VB
Public Function Find ( 
	keyName As String
) As IniKey
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniKeyCollection
Dim keyName As String
Dim returnValue As IniKey

returnValue = instance.Find(keyName)
```

**C++**<br />
``` C++
public:
IniKey^ Find(
	String^ keyName
)
```

**F#**<br />
``` F#
member Find : 
        keyName : string -> IniKey 

```


#### Parameters
&nbsp;<dl><dt>keyName</dt><dd>Type: System.String<br />The key name.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a><br /><a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />