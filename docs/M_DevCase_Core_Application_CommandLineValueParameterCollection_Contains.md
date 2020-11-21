# CommandLineValueParameterCollection.Contains Method 
 

Determines whether the <a href="T_DevCase_Core_Application_CommandLineValueParameterCollection">CommandLineValueParameterCollection</a> contains a <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> that matches the specified key name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool Contains(
	string name
)
```

**VB**<br />
``` VB
Public Function Contains ( 
	name As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineValueParameterCollection
Dim name As String
Dim returnValue As Boolean

returnValue = instance.Contains(name)
```

**C++**<br />
``` C++
public:
bool Contains(
	String^ name
)
```

**F#**<br />
``` F#
member Contains : 
        name : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the parameter.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the <a href="T_DevCase_Core_Application_CommandLineValueParameterCollection">CommandLineValueParameterCollection</a> contains the <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a>, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineValueParameterCollection">CommandLineValueParameterCollection Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />