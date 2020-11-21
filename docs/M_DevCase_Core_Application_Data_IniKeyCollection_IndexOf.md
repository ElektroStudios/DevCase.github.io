# IniKeyCollection.IndexOf Method 
 

Searches for an <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> that matches the specified key name and returns the zero-based index of the first occurrence within the entire <a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int IndexOf(
	string keyName
)
```

**VB**<br />
``` VB
Public Function IndexOf ( 
	keyName As String
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniKeyCollection
Dim keyName As String
Dim returnValue As Integer

returnValue = instance.IndexOf(keyName)
```

**C++**<br />
``` C++
public:
int IndexOf(
	String^ keyName
)
```

**F#**<br />
``` F#
member IndexOf : 
        keyName : string -> int 

```


#### Parameters
&nbsp;<dl><dt>keyName</dt><dd>Type: System.String<br />The key name.</dd></dl>

#### Return Value
Type: Int32<br />The zero-based index of the first occurrence of <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> within the entire <a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection</a>, if found; otherwise, `–1`.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />