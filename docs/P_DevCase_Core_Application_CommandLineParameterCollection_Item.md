# CommandLineParameterCollection.Item Property 
 

Gets or sets the <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> that matches the specified key name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CommandLineParameter this[
	string paramName
] { get; set; }
```

**VB**<br />
``` VB
Public Property Item ( 
	paramName As String
) As CommandLineParameter
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineParameterCollection
Dim paramName As String
Dim value As CommandLineParameter

value = instance.Item(paramName)

instance.Item(paramName) = value
```

**C++**<br />
``` C++
public:
property CommandLineParameter^ Item[String^ paramName] {
	CommandLineParameter^ get (String^ paramName);
	void set (String^ paramName, CommandLineParameter^ value);
}
```

**F#**<br />
``` F#
member Item : CommandLineParameter with get, set

```


#### Parameters
&nbsp;<dl><dt>paramName</dt><dd>Type: System.String<br />The parameter name.</dd></dl>

#### Property Value
Type: <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a><br />The <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineParameterCollection">CommandLineParameterCollection Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />