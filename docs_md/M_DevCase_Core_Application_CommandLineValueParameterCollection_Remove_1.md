# CommandLineValueParameterCollection.Remove Method (String)
 

Removes a <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> from the <a href="T_DevCase_Core_Application_CommandLineValueParameterCollection">CommandLineValueParameterCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Remove(
	string name
)
```

**VB**<br />
``` VB
Public Sub Remove ( 
	name As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineValueParameterCollection
Dim name As String

instance.Remove(name)
```

**C++**<br />
``` C++
public:
void Remove(
	String^ name
)
```

**F#**<br />
``` F#
member Remove : 
        name : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the parameter.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Parameter doesn't exists.;name</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineValueParameterCollection">CommandLineValueParameterCollection Class</a><br /><a href="Overload_DevCase_Core_Application_CommandLineValueParameterCollection_Remove">Remove Overload</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />