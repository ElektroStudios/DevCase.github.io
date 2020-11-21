# IniSectionCollection.IndexOf Method 
 

Searches for an <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> that matches the specified section name and returns the zero-based index of the first occurrence within the entire <a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int IndexOf(
	string sectionName
)
```

**VB**<br />
``` VB
Public Function IndexOf ( 
	sectionName As String
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniSectionCollection
Dim sectionName As String
Dim returnValue As Integer

returnValue = instance.IndexOf(sectionName)
```

**C++**<br />
``` C++
public:
int IndexOf(
	String^ sectionName
)
```

**F#**<br />
``` F#
member IndexOf : 
        sectionName : string -> int 

```


#### Parameters
&nbsp;<dl><dt>sectionName</dt><dd>Type: System.String<br />The section name.</dd></dl>

#### Return Value
Type: Int32<br />The zero-based index of the first occurrence of <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> within the entire <a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection</a>, if found; otherwise, `–1`.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />