# WinStartupUtil.Remove Method 
 

Removes an application from Windows Startup through registry.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Remove(
	RegistryScope registryScope,
	WinStartupScope startupScope,
	SystemScope systemScope,
	string title,
	bool throwOnMissingValue = false
)
```

**VB**<br />
``` VB
Public Shared Sub Remove ( 
	registryScope As RegistryScope,
	startupScope As WinStartupScope,
	systemScope As SystemScope,
	title As String,
	Optional throwOnMissingValue As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim registryScope As RegistryScope
Dim startupScope As WinStartupScope
Dim systemScope As SystemScope
Dim title As String
Dim throwOnMissingValue As BooleanWinStartupUtil.Remove(registryScope, startupScope, 
	systemScope, title, throwOnMissingValue)
```

**C++**<br />
``` C++
public:
static void Remove(
	RegistryScope registryScope, 
	WinStartupScope startupScope, 
	SystemScope systemScope, 
	String^ title, 
	bool throwOnMissingValue = false
)
```

**F#**<br />
``` F#
static member Remove : 
        registryScope : RegistryScope * 
        startupScope : WinStartupScope * 
        systemScope : SystemScope * 
        title : string * 
        ?throwOnMissingValue : bool 
(* Defaults:
        let _throwOnMissingValue = defaultArg throwOnMissingValue false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>registryScope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry user scope.</dd><dt>startupScope</dt><dd>Type: <a href="T_DevCase_Core_Shell_WinStartupScope">DevCase.Core.Shell.WinStartupScope</a><br />The win-startup key scope.</dd><dt>systemScope</dt><dd>Type: <a href="T_DevCase_Core_Shell_SystemScope">DevCase.Core.Shell.SystemScope</a><br />The system-key scope.</dd><dt>title</dt><dd>Type: System.String<br />The registry entry to find.</dd><dt>throwOnMissingValue (Optional)</dt><dd>Type: System.Boolean<br />if set to `true` (`True` in Visual Basic), throws an exception on missing value.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>title</td></tr><tr><td>ArgumentException</td><td>Registry value not found.;title</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
WinStartup.Remove(RegistryScope.CurrentUser, WinStartupScope.Run, SystemScope.System32,
                  title:="Application Title",
                  throwOnMissingValue:=True)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_WinStartupUtil">WinStartupUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />