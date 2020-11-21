# TweakingUtil.ShowSystemFiles Property 
 

**Note: This API is now obsolete.**

Gets or sets a value that determines whether the system will show system files.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("This functionality may not work.")]
public static bool ShowSystemFiles { get; set; }
```

**VB**<br />
``` VB
<ObsoleteAttribute("This functionality may not work.")>
Public Shared Property ShowSystemFiles As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.ShowSystemFiles

TweakingUtil.ShowSystemFiles = value
```

**C++**<br />
``` C++
public:
[ObsoleteAttribute(L"This functionality may not work.")]
static property bool ShowSystemFiles {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<ObsoleteAttribute("This functionality may not work.")>]
static member ShowSystemFiles : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if system files are shown, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />