# TweakingUtil.ConsoleBufferAmount Property 
 

Gets or sets the amount of buffers of the CMD, valid range is from `1` to `999`.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int ConsoleBufferAmount { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ConsoleBufferAmount As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = TweakingUtil.ConsoleBufferAmount

TweakingUtil.ConsoleBufferAmount = value
```

**C++**<br />
``` C++
public:
static property int ConsoleBufferAmount {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member ConsoleBufferAmount : int with get, set

```


#### Property Value
Type: Int32<br />The amount of buffers of the CMD, from `1` to `999`.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />