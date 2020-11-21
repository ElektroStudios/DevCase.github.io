# CommandLineParameterCollection.Remove Method (CommandLineParameter)
 

Removes a <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> from the <a href="T_DevCase_Core_Application_CommandLineParameterCollection">CommandLineParameterCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Remove(
	CommandLineParameter param
)
```

**VB**<br />
``` VB
Public Sub Remove ( 
	param As CommandLineParameter
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineParameterCollection
Dim param As CommandLineParameter

instance.Remove(param)
```

**C++**<br />
``` C++
public:
void Remove(
	CommandLineParameter^ param
)
```

**F#**<br />
``` F#
member Remove : 
        param : CommandLineParameter -> unit 

```


#### Parameters
&nbsp;<dl><dt>param</dt><dd>Type: <a href="T_DevCase_Core_Application_CommandLineParameter">DevCase.Core.Application.CommandLineParameter</a><br />The parameter.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Parameter doesn't exists.;name</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineParameterCollection">CommandLineParameterCollection Class</a><br /><a href="Overload_DevCase_Core_Application_CommandLineParameterCollection_Remove">Remove Overload</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />