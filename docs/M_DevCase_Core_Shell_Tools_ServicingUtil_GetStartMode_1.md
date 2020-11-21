# ServicingUtil.GetStartMode Method (String)
 

Gets the start mode of a service.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ServiceStartModeEx GetStartMode(
	string svcName
)
```

**VB**<br />
``` VB
Public Shared Function GetStartMode ( 
	svcName As String
) As ServiceStartModeEx
```

**VB Usage**<br />
``` VB Usage
Dim svcName As String
Dim returnValue As ServiceStartModeEx

returnValue = ServicingUtil.GetStartMode(svcName)
```

**C++**<br />
``` C++
public:
static ServiceStartModeEx GetStartMode(
	String^ svcName
)
```

**F#**<br />
``` F#
static member GetStartMode : 
        svcName : string -> ServiceStartModeEx 

```


#### Parameters
&nbsp;<dl><dt>svcName</dt><dd>Type: System.String<br />The service name.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Shell_ServiceStartModeEx">ServiceStartModeEx</a><br />The service's start mode.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Any service found with the specified name.</td></tr><tr><td>Exception</td><td>Registry value "Start" not found for service.</td></tr><tr><td>Exception</td><td>Registry value "DelayedAutoStart" not found for service.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim svcStartMode As ServiceStartModeEx = Servicing.GetStartMode("themes")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ServicingUtil">ServicingUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_ServicingUtil_GetStartMode">GetStartMode Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />