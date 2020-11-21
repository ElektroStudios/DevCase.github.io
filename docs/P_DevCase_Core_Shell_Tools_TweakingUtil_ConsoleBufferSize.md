# TweakingUtil.ConsoleBufferSize Property 
 

Gets or sets the buffer size of the CMD, valid range is from `1` to `999`.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int ConsoleBufferSize { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ConsoleBufferSize As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = TweakingUtil.ConsoleBufferSize

TweakingUtil.ConsoleBufferSize = value
```

**C++**<br />
``` C++
public:
static property int ConsoleBufferSize {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member ConsoleBufferSize : int with get, set

```


#### Property Value
Type: Int32<br />The buffer size of the CMD, from `1` to `999`.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />