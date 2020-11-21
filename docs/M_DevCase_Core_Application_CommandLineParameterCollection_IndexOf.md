# CommandLineParameterCollection.IndexOf Method 
 

Searches for an <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> that matches the specified key name and returns the zero-based index of the first occurrence within the entire <a href="T_DevCase_Core_Application_CommandLineParameterCollection">CommandLineParameterCollection</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int IndexOf(
	string name
)
```

**VB**<br />
``` VB
Public Function IndexOf ( 
	name As String
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineParameterCollection
Dim name As String
Dim returnValue As Integer

returnValue = instance.IndexOf(name)
```

**C++**<br />
``` C++
public:
int IndexOf(
	String^ name
)
```

**F#**<br />
``` F#
member IndexOf : 
        name : string -> int 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the parameter.</dd></dl>

#### Return Value
Type: Int32<br />The zero-based index of the first occurrence of <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> within the entire <a href="T_DevCase_Core_Application_CommandLineParameterCollection">CommandLineParameterCollection</a>, if found; otherwise, `–1`.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineParameterCollection">CommandLineParameterCollection Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />