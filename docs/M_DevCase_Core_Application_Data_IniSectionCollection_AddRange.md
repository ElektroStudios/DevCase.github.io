# IniSectionCollection.AddRange Method (IniSection[])
 

Adds the specified sections to the end of the <a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void AddRange(
	IniSection[] sections
)
```

**VB**<br />
``` VB
Public Sub AddRange ( 
	sections As IniSection()
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniSectionCollection
Dim sections As IniSection()

instance.AddRange(sections)
```

**C++**<br />
``` C++
public:
void AddRange(
	array<IniSection^>^ sections
)
```

**F#**<br />
``` F#
member AddRange : 
        sections : IniSection[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>sections</dt><dd>Type: <a href="T_DevCase_Core_Application_Data_IniSection">DevCase.Core.Application.Data.IniSection</a>[]<br />The sections to add.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Section already exists.;section</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection Class</a><br /><a href="Overload_DevCase_Core_Application_Data_IniSectionCollection_AddRange">AddRange Overload</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />