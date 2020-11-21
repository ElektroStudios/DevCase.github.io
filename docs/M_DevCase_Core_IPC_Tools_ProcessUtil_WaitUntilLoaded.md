# ProcessUtil.WaitUntilLoaded Method 
 

**Note: This API is now obsolete.**

Blocks the caller thread until te specified process has been fully loaded.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("Use method 'DevCase.Core.Extensions.Process.WaitForIdle()' instead")]
public static void WaitUntilLoaded(
	Process p,
	int timeOut = 1500
)
```

**VB**<br />
``` VB
<ObsoleteAttribute("Use method 'DevCase.Core.Extensions.Process.WaitForIdle()' instead")>
Public Shared Sub WaitUntilLoaded ( 
	p As Process,
	Optional timeOut As Integer = 1500
)
```

**VB Usage**<br />
``` VB Usage
Dim p As Process
Dim timeOut As Integer

ProcessUtil.WaitUntilLoaded(p, timeOut)
```

**C++**<br />
``` C++
public:
[ObsoleteAttribute(L"Use method 'DevCase.Core.Extensions.Process.WaitForIdle()' instead")]
static void WaitUntilLoaded(
	Process^ p, 
	int timeOut = 1500
)
```

**F#**<br />
``` F#
[<ObsoleteAttribute("Use method 'DevCase.Core.Extensions.Process.WaitForIdle()' instead")>]
static member WaitUntilLoaded : 
        p : Process * 
        ?timeOut : int 
(* Defaults:
        let _timeOut = defaultArg timeOut 1500
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>p</dt><dd>Type: System.Diagnostics.Process<br />\[Missing <param name="p"/> documentation for "M:DevCase.Core.IPC.Tools.ProcessUtil.WaitUntilLoaded(System.Diagnostics.Process,System.Int32)"\]</dd><dt>timeOut (Optional)</dt><dd>Type: System.Int32<br />\[Missing <param name="timeOut"/> documentation for "M:DevCase.Core.IPC.Tools.ProcessUtil.WaitUntilLoaded(System.Diagnostics.Process,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />