# TweakingUtil.ExtendedPathsEnabled Property 
 

Gets or sets a value that determines whether the extended-length paths is enabled on the current drive. 

 In `Windows` system, the maximum length for a path is composed of `260` characters, however, the `Windows API` has many functions that also have `Unicode` versions to permit an extended-length path for a maximum total path length of approximately `32.767` characters.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ExtendedPathsEnabled { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ExtendedPathsEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.ExtendedPathsEnabled

TweakingUtil.ExtendedPathsEnabled = value
```

**C++**<br />
``` C++
public:
static property bool ExtendedPathsEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member ExtendedPathsEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if extended-length paths is enabled on the current drive, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />