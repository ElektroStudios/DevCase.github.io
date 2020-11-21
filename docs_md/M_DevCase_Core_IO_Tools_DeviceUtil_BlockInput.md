# DeviceUtil.BlockInput Method 
 

Blocks the keyboard and mouse input events. 

 When blocked, the user cannot send keystrokes or use the mouse.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void BlockInput()
```

**VB**<br />
``` VB
Public Shared Sub BlockInput
```

**VB Usage**<br />
``` VB Usage

DeviceUtil.BlockInput()
```

**C++**<br />
``` C++
public:
static void BlockInput()
```

**F#**<br />
``` F#
static member BlockInput : unit -> unit 

```


## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>IOException</td><td>Input is already blocked.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />