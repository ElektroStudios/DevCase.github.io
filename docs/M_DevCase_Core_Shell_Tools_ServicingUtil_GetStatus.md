# ServicingUtil.GetStatus Method 
 

Gets the status of a service.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ServiceControllerStatus GetStatus(
	string svcName
)
```

**VB**<br />
``` VB
Public Shared Function GetStatus ( 
	svcName As String
) As ServiceControllerStatus
```

**VB Usage**<br />
``` VB Usage
Dim svcName As String
Dim returnValue As ServiceControllerStatus

returnValue = ServicingUtil.GetStatus(svcName)
```

**C++**<br />
``` C++
public:
static ServiceControllerStatus GetStatus(
	String^ svcName
)
```

**F#**<br />
``` F#
static member GetStatus : 
        svcName : string -> ServiceControllerStatus 

```


#### Parameters
&nbsp;<dl><dt>svcName</dt><dd>Type: System.String<br />The service name.</dd></dl>

#### Return Value
Type: ServiceControllerStatus<br />The service status.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Any service found with the specified name.;svcName</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim svcStatus As ServiceControllerStatus = Servicing.GetStatus("themes")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ServicingUtil">ServicingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />