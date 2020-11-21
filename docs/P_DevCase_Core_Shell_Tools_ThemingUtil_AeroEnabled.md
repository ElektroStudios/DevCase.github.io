# ThemingUtil.AeroEnabled Property 
 

Gets a value indicating whether Aero feature is enabled on the current operating system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool AeroEnabled { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property AeroEnabled As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = ThemingUtil.AeroEnabled

```

**C++**<br />
``` C++
public:
static property bool AeroEnabled {
	bool get ();
}
```

**F#**<br />
``` F#
static member AeroEnabled : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if Aero feature is enabled on the current operating system. 

`false` (`False` in Visual Basic) if Aero feature is not enabled or else is not supported by the current operating system (like Windows XP or previous versions).

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ThemingUtil">ThemingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />