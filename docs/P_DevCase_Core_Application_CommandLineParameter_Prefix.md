# CommandLineParameter.Prefix Property 
 

Gets or sets the prefix character that indicates the start of the parameter's name. 

 For example: "/ParameterName" where "/" is the prefix.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CommandLineParameterPrefix Prefix { get; set; }
```

**VB**<br />
``` VB
Public Property Prefix As CommandLineParameterPrefix
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineParameter
Dim value As CommandLineParameterPrefix

value = instance.Prefix

instance.Prefix = value
```

**C++**<br />
``` C++
public:
property CommandLineParameterPrefix Prefix {
	CommandLineParameterPrefix get ();
	void set (CommandLineParameterPrefix value);
}
```

**F#**<br />
``` F#
member Prefix : CommandLineParameterPrefix with get, set

```


#### Property Value
Type: <a href="T_DevCase_Core_Application_CommandLineParameterPrefix">CommandLineParameterPrefix</a><br />The prefix character that indicates the start of the parameter's name.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />