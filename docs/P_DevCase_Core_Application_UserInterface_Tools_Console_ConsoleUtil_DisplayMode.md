# ConsoleUtil.DisplayMode Property 
 

Gets the window handle of the console associated with the calling process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ConsoleDisplayMode DisplayMode { get; set; }
```

**VB**<br />
``` VB
Public Shared Property DisplayMode As ConsoleDisplayMode
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As ConsoleDisplayMode

value = ConsoleUtil.DisplayMode

ConsoleUtil.DisplayMode = value
```

**C++**<br />
``` C++
public:
static property ConsoleDisplayMode DisplayMode {
	ConsoleDisplayMode get ();
	void set (ConsoleDisplayMode value);
}
```

**F#**<br />
``` F#
static member DisplayMode : ConsoleDisplayMode with get, set

```


#### Property Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ConsoleDisplayMode">ConsoleDisplayMode</a><br />The window handle of the console associated with the calling process.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />