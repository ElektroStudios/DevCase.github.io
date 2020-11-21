# TweakingUtil.MinAnimate Property 
 

Gets or sets a value that determines whether a window animates while being resized.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool MinAnimate { get; set; }
```

**VB**<br />
``` VB
Public Shared Property MinAnimate As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.MinAnimate

TweakingUtil.MinAnimate = value
```

**C++**<br />
``` C++
public:
static property bool MinAnimate {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member MinAnimate : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) window animates while being resized, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="http://technet.microsoft.com/en-us/library/cc938230.aspx" target="_blank">http://technet.microsoft.com/en-us/library/cc938230.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />