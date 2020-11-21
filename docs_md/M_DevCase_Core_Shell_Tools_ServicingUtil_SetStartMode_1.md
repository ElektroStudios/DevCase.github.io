# ServicingUtil.SetStartMode Method (String, ServiceStartModeEx)
 

Sets the start mode of a service.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetStartMode(
	string svcName,
	ServiceStartModeEx startMode
)
```

**VB**<br />
``` VB
Public Shared Sub SetStartMode ( 
	svcName As String,
	startMode As ServiceStartModeEx
)
```

**VB Usage**<br />
``` VB Usage
Dim svcName As String
Dim startMode As ServiceStartModeExServicingUtil.SetStartMode(svcName, startMode)
```

**C++**<br />
``` C++
public:
static void SetStartMode(
	String^ svcName, 
	ServiceStartModeEx startMode
)
```

**F#**<br />
``` F#
static member SetStartMode : 
        svcName : string * 
        startMode : ServiceStartModeEx -> unit 

```


#### Parameters
&nbsp;<dl><dt>svcName</dt><dd>Type: System.String<br />The service name.</dd><dt>startMode</dt><dd>Type: <a href="T_DevCase_Core_Shell_ServiceStartModeEx">DevCase.Core.Shell.ServiceStartModeEx</a><br />The start mode.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Any service found with the specified name.</td></tr><tr><td>InvalidEnumArgumentException</td><td>startMode</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Servicing.SetStartMode("themes", ServiceStartModeEx.Automatic)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ServicingUtil">ServicingUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_ServicingUtil_SetStartMode">SetStartMode Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />