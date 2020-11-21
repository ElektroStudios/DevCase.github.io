# IniFile.SectionNames Property 
 

Gets the initialization file (INI) section names.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string[] SectionNames { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property SectionNames As String()
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniFile
Dim value As String()

value = instance.SectionNames

```

**C++**<br />
``` C++
public:
property array<String^>^ SectionNames {
	array<String^>^ get ();
}
```

**F#**<br />
``` F#
member SectionNames : string[] with get

```


#### Property Value
Type: String[]<br />The initialization file (INI) section names.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniFile">IniFile Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />