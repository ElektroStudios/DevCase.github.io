# TweakingUtil.BingSearchEnabled Property 
 

Gets or sets a value that determines whether Bing search is enabled in Windows searcher. 

 This feature is available only in window 10.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool BingSearchEnabled { get; set; }
```

**VB**<br />
``` VB
Public Shared Property BingSearchEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.BingSearchEnabled

TweakingUtil.BingSearchEnabled = value
```

**C++**<br />
``` C++
public:
static property bool BingSearchEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member BingSearchEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if Bing search is enabled, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />