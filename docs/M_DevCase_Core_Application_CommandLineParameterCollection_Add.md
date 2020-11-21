# CommandLineParameterCollection.Add Method 
 

Adds a <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> to the end of the <a href="T_DevCase_Core_Application_CommandLineParameterCollection">CommandLineParameterCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Add(
	CommandLineParameter param
)
```

**VB**<br />
``` VB
Public Sub Add ( 
	param As CommandLineParameter
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineParameterCollection
Dim param As CommandLineParameter

instance.Add(param)
```

**C++**<br />
``` C++
public:
void Add(
	CommandLineParameter^ param
)
```

**F#**<br />
``` F#
member Add : 
        param : CommandLineParameter -> unit 

```


#### Parameters
&nbsp;<dl><dt>param</dt><dd>Type: <a href="T_DevCase_Core_Application_CommandLineParameter">DevCase.Core.Application.CommandLineParameter</a><br />The parameter to add.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Parameter already exists.;param</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineParameterCollection">CommandLineParameterCollection Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />