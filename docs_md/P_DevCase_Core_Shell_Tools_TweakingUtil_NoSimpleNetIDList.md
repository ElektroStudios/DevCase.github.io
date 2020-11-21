# TweakingUtil.NoSimpleNetIDList Property 
 

Gets or sets a value that determines whether network files or folders are automatically refreshed after you create, move or delete files or folders.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool NoSimpleNetIDList { get; set; }
```

**VB**<br />
``` VB
Public Shared Property NoSimpleNetIDList As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.NoSimpleNetIDList

TweakingUtil.NoSimpleNetIDList = value
```

**C++**<br />
``` C++
public:
static property bool NoSimpleNetIDList {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member NoSimpleNetIDList : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) to automatically refreshed network files or folders, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />