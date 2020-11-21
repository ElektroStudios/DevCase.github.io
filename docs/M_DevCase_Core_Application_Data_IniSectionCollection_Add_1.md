# IniSectionCollection.Add Method (String)
 

Adds a <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> to the end of the <a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Add(
	string sectionName
)
```

**VB**<br />
``` VB
Public Sub Add ( 
	sectionName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniSectionCollection
Dim sectionName As String

instance.Add(sectionName)
```

**C++**<br />
``` C++
public:
void Add(
	String^ sectionName
)
```

**F#**<br />
``` F#
member Add : 
        sectionName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>sectionName</dt><dd>Type: System.String<br />The section name to add.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Section already exists.;section</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection Class</a><br /><a href="Overload_DevCase_Core_Application_Data_IniSectionCollection_Add">Add Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />