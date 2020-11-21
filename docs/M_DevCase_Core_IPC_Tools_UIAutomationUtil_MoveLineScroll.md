# UIAutomationUtil.MoveLineScroll Method 
 

Moves the specified line scroll of an EDIT control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void MoveLineScroll(
	IntPtr handle,
	ScrollDirection scrollDirection,
	int scrollCount
)
```

**VB**<br />
``` VB
Public Shared Sub MoveLineScroll ( 
	handle As IntPtr,
	scrollDirection As ScrollDirection,
	scrollCount As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim handle As IntPtr
Dim scrollDirection As ScrollDirection
Dim scrollCount As Integer

UIAutomationUtil.MoveLineScroll(handle, scrollDirection, 
	scrollCount)
```

**C++**<br />
``` C++
public:
static void MoveLineScroll(
	IntPtr handle, 
	ScrollDirection scrollDirection, 
	int scrollCount
)
```

**F#**<br />
``` F#
static member MoveLineScroll : 
        handle : IntPtr * 
        scrollDirection : ScrollDirection * 
        scrollCount : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: System.IntPtr<br />The scrollbar's handle.</dd><dt>scrollDirection</dt><dd>Type: <a href="T_DevCase_Core_IPC_ScrollDirection">DevCase.Core.IPC.ScrollDirection</a><br />The scroll direction.</dd><dt>scrollCount</dt><dd>Type: System.Int32<br />The amount of lines to scroll.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
MoveLineScroll(TextBox1.Handle, ScrollDirection.Down, 1)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />