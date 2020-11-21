# AppUtil.SetIEBrowserEmulationMode Method (Process, RegistryScope, IEBrowserEmulationMode)
 

Sets the Internet Explorer browser emulation mode for the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetIEBrowserEmulationMode(
	Process p,
	RegistryScope scope,
	IEBrowserEmulationMode mode
)
```

**VB**<br />
``` VB
Public Shared Sub SetIEBrowserEmulationMode ( 
	p As Process,
	scope As RegistryScope,
	mode As IEBrowserEmulationMode
)
```

**VB Usage**<br />
``` VB Usage
Dim p As Process
Dim scope As RegistryScope
Dim mode As IEBrowserEmulationModeAppUtil.SetIEBrowserEmulationMode(p, 
	scope, mode)
```

**C++**<br />
``` C++
public:
static void SetIEBrowserEmulationMode(
	Process^ p, 
	RegistryScope scope, 
	IEBrowserEmulationMode mode
)
```

**F#**<br />
``` F#
static member SetIEBrowserEmulationMode : 
        p : Process * 
        scope : RegistryScope * 
        mode : IEBrowserEmulationMode -> unit 

```


#### Parameters
&nbsp;<dl><dt>p</dt><dd>Type: System.Diagnostics.Process<br />The process.</dd><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd><dt>mode</dt><dd>Type: <a href="T_DevCase_Core_NET_IEBrowserEmulationMode">DevCase.Core.NET.IEBrowserEmulationMode</a><br />The Internet Explorer browser emulation mode to set.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>NotSupportedException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim processName As Process = Process.GetCurrentProcess()
Dim scope As RegistryScope = RegistryScope.CurrentUser
Dim oldMode As IEBrowserEmulationMode
Dim newMode As IEBrowserEmulationMode

oldMode = GetIEBrowserEmulationMode(p, scope)
SetIEBrowserEmulationMode(p, scope, IEBrowserEmulationMode.IE11Edge)
newMode = GetIEBrowserEmulationMode(p, scope)

Console.WriteLine(String.Format("Old Mode: {0} ({1})", oldMode, CStr(oldMode)))
Console.WriteLine(String.Format("New Mode: {0} ({1})", newMode, CStr(newMode)))

Dim f As New Form() With {.Size = New Size(1280, 720)}
Dim wb As New WebBrowser With {.Dock = DockStyle.Fill}
f.Controls.Add(wb)
f.Show()
wb.Navigate("http://www.whatversion.net/browser/")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_AppUtil_SetIEBrowserEmulationMode">SetIEBrowserEmulationMode Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />

#### Other Resources
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/general-info/ee330730(v=vs.85)" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/general-info/ee330730(v=vs.85)</a><br />