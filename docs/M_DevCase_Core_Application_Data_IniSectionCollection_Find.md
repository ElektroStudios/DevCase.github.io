# IniSectionCollection.Find Method 
 

Searches for an <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> that matches the specified section name, and returns the first occurrence within the entire <a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IniSection Find(
	string sectionName
)
```

**VB**<br />
``` VB
Public Function Find ( 
	sectionName As String
) As IniSection
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniSectionCollection
Dim sectionName As String
Dim returnValue As IniSection

returnValue = instance.Find(sectionName)
```

**C++**<br />
``` C++
public:
IniSection^ Find(
	String^ sectionName
)
```

**F#**<br />
``` F#
member Find : 
        sectionName : string -> IniSection 

```


#### Parameters
&nbsp;<dl><dt>sectionName</dt><dd>Type: System.String<br />The section name.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a><br /><a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />