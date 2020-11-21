# IniSectionCollection.Contains Method 
 

Determines whether the <a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection</a> contains a <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> that matches the specified section name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool Contains(
	string sectionName
)
```

**VB**<br />
``` VB
Public Function Contains ( 
	sectionName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniSectionCollection
Dim sectionName As String
Dim returnValue As Boolean

returnValue = instance.Contains(sectionName)
```

**C++**<br />
``` C++
public:
bool Contains(
	String^ sectionName
)
```

**F#**<br />
``` F#
member Contains : 
        sectionName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>sectionName</dt><dd>Type: System.String<br />The section name.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the <a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection</a> contains the <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a>, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />