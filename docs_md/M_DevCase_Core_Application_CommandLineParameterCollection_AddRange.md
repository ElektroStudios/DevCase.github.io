# CommandLineParameterCollection.AddRange Method 
 

Adds the specified parameters to the end of the <a href="T_DevCase_Core_Application_CommandLineParameterCollection">CommandLineParameterCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void AddRange(
	CommandLineParameter[] params
)
```

**VB**<br />
``` VB
Public Sub AddRange ( 
	params As CommandLineParameter()
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineParameterCollection
Dim params As CommandLineParameter()

instance.AddRange(params)
```

**C++**<br />
``` C++
public:
void AddRange(
	array<CommandLineParameter^>^ params
)
```

**F#**<br />
``` F#
member AddRange : 
        params : CommandLineParameter[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>params</dt><dd>Type: <a href="T_DevCase_Core_Application_CommandLineParameter">DevCase.Core.Application.CommandLineParameter</a>[]<br />The parameters to add.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Parameter already exists.;param</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineParameterCollection">CommandLineParameterCollection Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />