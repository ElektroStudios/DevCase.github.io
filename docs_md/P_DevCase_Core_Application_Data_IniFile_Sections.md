# IniFile.Sections Property 
 

Gets or sets the initialization file (INI) sections.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IniSectionCollection Sections { get; set; }
```

**VB**<br />
``` VB
Public Property Sections As IniSectionCollection
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniFile
Dim value As IniSectionCollection

value = instance.Sections

instance.Sections = value
```

**C++**<br />
``` C++
public:
property IniSectionCollection^ Sections {
	IniSectionCollection^ get ();
	void set (IniSectionCollection^ value);
}
```

**F#**<br />
``` F#
member Sections : IniSectionCollection with get, set

```


#### Property Value
Type: <a href="T_DevCase_Core_Application_Data_IniSectionCollection">IniSectionCollection</a><br />The initialization file (INI) sections.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniFile">IniFile Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />