# AppUtil.GetIEBrowserEmulationMode Method (Process, RegistryScope)
 

Gets the Internet Explorer browser emulation mode for the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEBrowserEmulationMode GetIEBrowserEmulationMode(
	Process p,
	RegistryScope scope
)
```

**VB**<br />
``` VB
Public Shared Function GetIEBrowserEmulationMode ( 
	p As Process,
	scope As RegistryScope
) As IEBrowserEmulationMode
```

**VB Usage**<br />
``` VB Usage
Dim p As Process
Dim scope As RegistryScope
Dim returnValue As IEBrowserEmulationMode

returnValue = AppUtil.GetIEBrowserEmulationMode(p, 
	scope)
```

**C++**<br />
``` C++
public:
static IEBrowserEmulationMode GetIEBrowserEmulationMode(
	Process^ p, 
	RegistryScope scope
)
```

**F#**<br />
``` F#
static member GetIEBrowserEmulationMode : 
        p : Process * 
        scope : RegistryScope -> IEBrowserEmulationMode 

```


#### Parameters
&nbsp;<dl><dt>p</dt><dd>Type: System.Diagnostics.Process<br />The process.</dd><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_NET_IEBrowserEmulationMode">IEBrowserEmulationMode</a><br />The resulting <a href="T_DevCase_Core_NET_IEBrowserEmulationMode">IEBrowserEmulationMode</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>NotSupportedException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim p As Process = Process.GetCurrentProcess()
Dim scope As RegistryScope = RegistryScope.CurrentUser
Dim mode As IEBrowserEmulationMode = GetIEBrowserEmulationMode(p, scope)

Console.WriteLine(String.Format("Mode: {0} ({1})", mode, CStr(mode)))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_AppUtil_GetIEBrowserEmulationMode">GetIEBrowserEmulationMode Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />

#### Other Resources
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/general-info/ee330730(v=vs.85)" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/general-info/ee330730(v=vs.85)</a><br />