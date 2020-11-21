# AppletsUtil.ShowShellAboutDialog Method (String, String, Icon)
 

Displays a Shell-About dialog box with custom message and icon.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ShowShellAboutDialog(
	string windowTitle,
	string headerText,
	Icon icon = null
)
```

**VB**<br />
``` VB
Public Shared Sub ShowShellAboutDialog ( 
	windowTitle As String,
	headerText As String,
	Optional icon As Icon = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim windowTitle As String
Dim headerText As String
Dim icon As IconAppletsUtil.ShowShellAboutDialog(windowTitle, 
	headerText, icon)
```

**C++**<br />
``` C++
public:
static void ShowShellAboutDialog(
	String^ windowTitle, 
	String^ headerText, 
	Icon^ icon = nullptr
)
```

**F#**<br />
``` F#
static member ShowShellAboutDialog : 
        windowTitle : string * 
        headerText : string * 
        ?icon : Icon 
(* Defaults:
        let _icon = defaultArg icon null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>windowTitle</dt><dd>Type: System.String<br />The window title.</dd><dt>headerText</dt><dd>Type: System.String<br />The header text.</dd><dt>icon (Optional)</dt><dd>Type: System.Drawing.Icon<br />The icon to display.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
ShowShellAboutDialog("Window Title", "Header Text", SystemIcons.Information)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_AppletsUtil">AppletsUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_AppletsUtil_ShowShellAboutDialog">ShowShellAboutDialog Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />