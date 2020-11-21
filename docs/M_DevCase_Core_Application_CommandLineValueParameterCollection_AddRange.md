# CommandLineValueParameterCollection.AddRange Method 
 

Adds the specified parameters to the end of the <a href="T_DevCase_Core_Application_CommandLineValueParameterCollection">CommandLineValueParameterCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void AddRange(
	CommandLineValueParameter<IConvertible>[] params
)
```

**VB**<br />
``` VB
Public Sub AddRange ( 
	params As CommandLineValueParameter(Of IConvertible)()
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineValueParameterCollection
Dim params As CommandLineValueParameter(Of IConvertible)()

instance.AddRange(params)
```

**C++**<br />
``` C++
public:
void AddRange(
	array<CommandLineValueParameter<IConvertible^>^>^ params
)
```

**F#**<br />
``` F#
member AddRange : 
        params : CommandLineValueParameter<IConvertible>[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>params</dt><dd>Type: <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">DevCase.Core.Application.CommandLineValueParameter</a>(IConvertible)[]<br />The parameters to add.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Parameter already exists.;param</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineValueParameterCollection">CommandLineValueParameterCollection Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />