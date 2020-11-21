# AppUtil.BrowserEmulationMode Property 
 

Gets or sets the Internet Explorer browser emulation mode for the current application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEBrowserEmulationMode this[
	RegistryScope scope
] { get; set; }
```

**VB**<br />
``` VB
Public Shared Property BrowserEmulationMode ( 
	scope As RegistryScope
) As IEBrowserEmulationMode
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim scope As RegistryScope
Dim value As IEBrowserEmulationMode

value = AppUtil.BrowserEmulationMode(scope)

AppUtil.BrowserEmulationMode(scope) = value
```

**C++**<br />
``` C++
public:
static property IEBrowserEmulationMode BrowserEmulationMode[RegistryScope scope] {
	IEBrowserEmulationMode get (RegistryScope scope);
	void set (RegistryScope scope, IEBrowserEmulationMode value);
}
```

**F#**<br />
``` F#
static member BrowserEmulationMode : IEBrowserEmulationMode with get, set

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd></dl>

#### Property Value
Type: <a href="T_DevCase_Core_NET_IEBrowserEmulationMode">IEBrowserEmulationMode</a><br />The Internet Explorer browser emulation mode.

## Examples
This is a code example to get, set and verify the IE browser emulation mode for the current process. 
**VB**<br />
``` VB
Dim scope As RegistryScope = RegistryScope.CurrentUser
Dim oldMode As IEBrowserEmulationMode
Dim newMode As IEBrowserEmulationMode

oldMode = BrowserEmulationMode(scope)
BrowserEmulationMode(scope) = IEBrowserEmulationMode.IE11Edge
newMode = BrowserEmulationMode(scope)

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
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />

#### Other Resources
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/general-info/ee330730(v=vs.85)" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/general-info/ee330730(v=vs.85)</a><br />