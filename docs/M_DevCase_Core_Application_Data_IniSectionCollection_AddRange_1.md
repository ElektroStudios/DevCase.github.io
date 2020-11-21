# IniSectionCollection.AddRange Method (String[])
 

Adds the specified section names to the end of the <a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void AddRange(
	string[] sectionNames
)
```

**VB**<br />
``` VB
Public Sub AddRange ( 
	sectionNames As String()
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniSectionCollection
Dim sectionNames As String()

instance.AddRange(sectionNames)
```

**C++**<br />
``` C++
public:
void AddRange(
	array<String^>^ sectionNames
)
```

**F#**<br />
``` F#
member AddRange : 
        sectionNames : string[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>sectionNames</dt><dd>Type: System.String[]<br />The section names to add.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Section already exists.;section</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection Class</a><br /><a href="Overload_DevCase_Core_Application_Data_IniSectionCollection_AddRange">AddRange Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />