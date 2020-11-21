# CommandLineValueParameter(*T*).Suffix Property 
 

Gets or sets the suffix character that delimits the parameter's name from the parameter's value. 

 For example: "/ParameterName=Value" where "/" is the prefix and "=" the suffix.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CommandLineParameterSuffix Suffix { get; set; }
```

**VB**<br />
``` VB
Public Property Suffix As CommandLineParameterSuffix
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineValueParameter
Dim value As CommandLineParameterSuffix

value = instance.Suffix

instance.Suffix = value
```

**C++**<br />
``` C++
public:
property CommandLineParameterSuffix Suffix {
	CommandLineParameterSuffix get ();
	void set (CommandLineParameterSuffix value);
}
```

**F#**<br />
``` F#
member Suffix : CommandLineParameterSuffix with get, set

```


#### Property Value
Type: <a href="T_DevCase_Core_Application_CommandLineParameterSuffix">CommandLineParameterSuffix</a><br />The suffix character that delimits the parameter's name from the parameter's value.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T) Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />