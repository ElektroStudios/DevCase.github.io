# CommandLineValueParameterCollection.Find Method 
 

Searches for an <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> that matches the specified parameter name, and returns the first occurrence within the entire <a href="T_DevCase_Core_Application_CommandLineValueParameterCollection">CommandLineValueParameterCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CommandLineValueParameter<IConvertible> Find(
	string name
)
```

**VB**<br />
``` VB
Public Function Find ( 
	name As String
) As CommandLineValueParameter(Of IConvertible)
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineValueParameterCollection
Dim name As String
Dim returnValue As CommandLineValueParameter(Of IConvertible)

returnValue = instance.Find(name)
```

**C++**<br />
``` C++
public:
CommandLineValueParameter<IConvertible^>^ Find(
	String^ name
)
```

**F#**<br />
``` F#
member Find : 
        name : string -> CommandLineValueParameter<IConvertible> 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the parameter.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter</a>(IConvertible)<br /><a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineValueParameterCollection">CommandLineValueParameterCollection Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />