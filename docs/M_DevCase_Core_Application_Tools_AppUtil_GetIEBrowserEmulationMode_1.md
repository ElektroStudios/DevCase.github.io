# AppUtil.GetIEBrowserEmulationMode Method (String, RegistryScope)
 

Gets the Internet Explorer browser emulation mode for the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEBrowserEmulationMode GetIEBrowserEmulationMode(
	string processName,
	RegistryScope scope
)
```

**VB**<br />
``` VB
Public Shared Function GetIEBrowserEmulationMode ( 
	processName As String,
	scope As RegistryScope
) As IEBrowserEmulationMode
```

**VB Usage**<br />
``` VB Usage
Dim processName As String
Dim scope As RegistryScope
Dim returnValue As IEBrowserEmulationMode

returnValue = AppUtil.GetIEBrowserEmulationMode(processName, 
	scope)
```

**C++**<br />
``` C++
public:
static IEBrowserEmulationMode GetIEBrowserEmulationMode(
	String^ processName, 
	RegistryScope scope
)
```

**F#**<br />
``` F#
static member GetIEBrowserEmulationMode : 
        processName : string * 
        scope : RegistryScope -> IEBrowserEmulationMode 

```


#### Parameters
&nbsp;<dl><dt>processName</dt><dd>Type: System.String<br />The process name (eg. 'cmd.exe').</dd><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_NET_IEBrowserEmulationMode">IEBrowserEmulationMode</a><br />The resulting <a href="T_DevCase_Core_NET_IEBrowserEmulationMode">IEBrowserEmulationMode</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>NotSupportedException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim processName As String = Process.GetCurrentProcess().ProcessName
Dim scope As RegistryScope = RegistryScope.CurrentUser
Dim mode As IEBrowserEmulationMode = GetIEBrowserEmulationMode(processName, scope)

Console.WriteLine(String.Format("Mode: {0} ({1})", mode, CStr(mode)))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_AppUtil_GetIEBrowserEmulationMode">GetIEBrowserEmulationMode Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />

#### Other Resources
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/general-info/ee330730(v=vs.85)" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/general-info/ee330730(v=vs.85)</a><br />