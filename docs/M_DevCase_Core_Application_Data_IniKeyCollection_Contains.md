# IniKeyCollection.Contains Method 
 

Determines whether the <a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection</a> contains a <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> that matches the specified key name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool Contains(
	string keyName
)
```

**VB**<br />
``` VB
Public Function Contains ( 
	keyName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniKeyCollection
Dim keyName As String
Dim returnValue As Boolean

returnValue = instance.Contains(keyName)
```

**C++**<br />
``` C++
public:
bool Contains(
	String^ keyName
)
```

**F#**<br />
``` F#
member Contains : 
        keyName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>keyName</dt><dd>Type: System.String<br />The key name.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the <a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection</a> contains the <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a>, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />