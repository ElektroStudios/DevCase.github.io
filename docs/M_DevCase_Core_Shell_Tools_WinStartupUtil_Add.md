# WinStartupUtil.Add Method 
 

Adds an application to Windows Startup through registry.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Add(
	RegistryScope registryScope,
	WinStartupScope startupScope,
	SystemScope systemScope,
	string title,
	string filePath,
	string arguments = "",
	bool secureModeByPass = false
)
```

**VB**<br />
``` VB
Public Shared Sub Add ( 
	registryScope As RegistryScope,
	startupScope As WinStartupScope,
	systemScope As SystemScope,
	title As String,
	filePath As String,
	Optional arguments As String = "",
	Optional secureModeByPass As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim registryScope As RegistryScope
Dim startupScope As WinStartupScope
Dim systemScope As SystemScope
Dim title As String
Dim filePath As String
Dim arguments As String
Dim secureModeByPass As BooleanWinStartupUtil.Add(registryScope, startupScope, 
	systemScope, title, filePath, arguments, 
	secureModeByPass)
```

**C++**<br />
``` C++
public:
static void Add(
	RegistryScope registryScope, 
	WinStartupScope startupScope, 
	SystemScope systemScope, 
	String^ title, 
	String^ filePath, 
	String^ arguments = L"", 
	bool secureModeByPass = false
)
```

**F#**<br />
``` F#
static member Add : 
        registryScope : RegistryScope * 
        startupScope : WinStartupScope * 
        systemScope : SystemScope * 
        title : string * 
        filePath : string * 
        ?arguments : string * 
        ?secureModeByPass : bool 
(* Defaults:
        let _arguments = defaultArg arguments ""
        let _secureModeByPass = defaultArg secureModeByPass false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>registryScope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry user scope.</dd><dt>startupScope</dt><dd>Type: <a href="T_DevCase_Core_Shell_WinStartupScope">DevCase.Core.Shell.WinStartupScope</a><br />The win-startup key scope.</dd><dt>systemScope</dt><dd>Type: <a href="T_DevCase_Core_Shell_SystemScope">DevCase.Core.Shell.SystemScope</a><br />The system-key scope.</dd><dt>title</dt><dd>Type: System.String<br />The registry entry title.</dd><dt>filePath</dt><dd>Type: System.String<br />The application file path.</dd><dt>arguments (Optional)</dt><dd>Type: System.String<br />\[Missing <param name="arguments"/> documentation for "M:DevCase.Core.Shell.Tools.WinStartupUtil.Add(DevCase.Core.Shell.RegistryScope,DevCase.Core.Shell.WinStartupScope,DevCase.Core.Shell.SystemScope,System.String,System.String,System.String,System.Boolean)"\]</dd><dt>secureModeByPass (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the file is ran even when the user logs into 'Secure Mode' on Windows.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>title or filePath</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
WinStartup.Add(RegistryScope.CurrentUser, WinStartupScope.Run, SystemScope.System32,
               title:="Application Title",
               filePath:="C:\Application.exe",
               arguments:="/Arg1",
               secureModeByPass:=True)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_WinStartupUtil">WinStartupUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />