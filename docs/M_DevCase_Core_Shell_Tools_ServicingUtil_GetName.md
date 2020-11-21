# ServicingUtil.GetName Method 
 

Gets the name of a service.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetName(
	string svcDisplayName
)
```

**VB**<br />
``` VB
Public Shared Function GetName ( 
	svcDisplayName As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim svcDisplayName As String
Dim returnValue As String

returnValue = ServicingUtil.GetName(svcDisplayName)
```

**C++**<br />
``` C++
public:
static String^ GetName(
	String^ svcDisplayName
)
```

**F#**<br />
``` F#
static member GetName : 
        svcDisplayName : string -> string 

```


#### Parameters
&nbsp;<dl><dt>svcDisplayName</dt><dd>Type: System.String<br />The service's display name.</dd></dl>

#### Return Value
Type: String<br />The service name.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Any service found with the specified display name.;svcDisplayName</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ServicingUtil">ServicingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />