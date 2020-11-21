# IniSectionCollection.Item Property 
 

Gets or sets the <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a> that matches the specified section name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IniSection this[
	string sectionName
] { get; set; }
```

**VB**<br />
``` VB
Public Property Item ( 
	sectionName As String
) As IniSection
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniSectionCollection
Dim sectionName As String
Dim value As IniSection

value = instance.Item(sectionName)

instance.Item(sectionName) = value
```

**C++**<br />
``` C++
public:
property IniSection^ Item[String^ sectionName] {
	IniSection^ get (String^ sectionName);
	void set (String^ sectionName, IniSection^ value);
}
```

**F#**<br />
``` F#
member Item : IniSection with get, set

```


#### Parameters
&nbsp;<dl><dt>sectionName</dt><dd>Type: System.String<br />The section name.</dd></dl>

#### Property Value
Type: <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a><br />The <a href="T_DevCase_Core_Application_Data_IniSection">IniSection</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />