# IniKeyCollection.Item Property 
 

Gets or sets the <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a> that matches the specified key name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IniKey this[
	string keyName
] { get; set; }
```

**VB**<br />
``` VB
Public Property Item ( 
	keyName As String
) As IniKey
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As IniKeyCollection
Dim keyName As String
Dim value As IniKey

value = instance.Item(keyName)

instance.Item(keyName) = value
```

**C++**<br />
``` C++
public:
property IniKey^ Item[String^ keyName] {
	IniKey^ get (String^ keyName);
	void set (String^ keyName, IniKey^ value);
}
```

**F#**<br />
``` F#
member Item : IniKey with get, set

```


#### Parameters
&nbsp;<dl><dt>keyName</dt><dd>Type: System.String<br />The key name.</dd></dl>

#### Property Value
Type: <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a><br />The <a href="T_DevCase_Core_Application_Data_IniKey">IniKey</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_IniKeyCollection">IniKeyCollection Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />