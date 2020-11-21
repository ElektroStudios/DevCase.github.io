# TweakingUtil.DefragBootOptimizeEnabled Property 
 

Gets or sets a value that determines whether Defragmentation's Boot optimization is enabled. 

 Windows automatically optimizes the file location for boot optimization. This optimization occurs automatically if the system is idle for 10 minutes. 

 Boot optimization improves startup time by locating startup files in contiguous clusters on the volume, reducing the movement of the disk head when reading the volume.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool DefragBootOptimizeEnabled { get; set; }
```

**VB**<br />
``` VB
Public Shared Property DefragBootOptimizeEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.DefragBootOptimizeEnabled

TweakingUtil.DefragBootOptimizeEnabled = value
```

**C++**<br />
``` C++
public:
static property bool DefragBootOptimizeEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member DefragBootOptimizeEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if Defragmentation's Boot optimization is enabled, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="http://technet.microsoft.com/en-us/library/cc784391(v=ws.10).aspx" target="_blank">http://technet.microsoft.com/en-us/library/cc784391(v=ws.10).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />