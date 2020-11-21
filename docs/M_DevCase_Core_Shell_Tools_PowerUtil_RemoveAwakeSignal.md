# PowerUtil.RemoveAwakeSignal Method 
 

Removes any previously sent Awake signal. 

 Call this function to return to previous state when the caller thread has finished.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool RemoveAwakeSignal()
```

**VB**<br />
``` VB
Public Shared Function RemoveAwakeSignal As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = PowerUtil.RemoveAwakeSignal()
```

**C++**<br />
``` C++
public:
static bool RemoveAwakeSignal()
```

**F#**<br />
``` F#
static member RemoveAwakeSignal : unit -> bool 

```


#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if operation succeeds, `false` (`False` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_PowerUtil">PowerUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />