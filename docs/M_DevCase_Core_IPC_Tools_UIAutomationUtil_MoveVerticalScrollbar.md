# UIAutomationUtil.MoveVerticalScrollbar Method 
 

Performs a scroll up or down on the specified scrollbar control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void MoveVerticalScrollbar(
	IntPtr handle,
	VerticalScrollDirection scrollDirection,
	short scrollCount = 1
)
```

**VB**<br />
``` VB
Public Shared Sub MoveVerticalScrollbar ( 
	handle As IntPtr,
	scrollDirection As VerticalScrollDirection,
	Optional scrollCount As Short = 1
)
```

**VB Usage**<br />
``` VB Usage
Dim handle As IntPtr
Dim scrollDirection As VerticalScrollDirection
Dim scrollCount As Short

UIAutomationUtil.MoveVerticalScrollbar(handle, 
	scrollDirection, scrollCount)
```

**C++**<br />
``` C++
public:
static void MoveVerticalScrollbar(
	IntPtr handle, 
	VerticalScrollDirection scrollDirection, 
	short scrollCount = 1
)
```

**F#**<br />
``` F#
static member MoveVerticalScrollbar : 
        handle : IntPtr * 
        scrollDirection : VerticalScrollDirection * 
        ?scrollCount : int16 
(* Defaults:
        let _scrollCount = defaultArg scrollCount 1
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: System.IntPtr<br />The scrollbar's handle.</dd><dt>scrollDirection</dt><dd>Type: <a href="T_DevCase_Core_IPC_VerticalScrollDirection">DevCase.Core.IPC.VerticalScrollDirection</a><br />The vertical scroll direction.</dd><dt>scrollCount (Optional)</dt><dd>Type: System.Int16<br />The amount of times to scroll.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
MoveVerticalScrollbar(VScrollBar1.Handle, VerticalScrollDirection.Down, 1)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />