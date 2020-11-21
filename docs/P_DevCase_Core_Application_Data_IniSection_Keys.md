# IniSection.Keys Property 
 

Gets or sets the section keys.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IniKeyCollection Keys { get; set; }
```

**VB**<br />
``` VB
Public Property Keys As IniKeyCollection
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniSection
Dim value As IniKeyCollection

value = instance.Keys

instance.Keys = value
```

**C++**<br />
``` C++
public:
property IniKeyCollection^ Keys {
	IniKeyCollection^ get ();
	void set (IniKeyCollection^ value);
}
```

**F#**<br />
``` F#
member Keys : IniKeyCollection with get, set

```


#### Property Value
Type: <a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection</a><br />The section keys.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniSection">IniSection Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />