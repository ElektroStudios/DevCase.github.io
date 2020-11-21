# ClipboardUtil.IsEmpty Method 
 

Determines whether the clipboard content is empty.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsEmpty()
```

**VB**<br />
``` VB
Public Shared Function IsEmpty As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = ClipboardUtil.IsEmpty()
```

**C++**<br />
``` C++
public:
static bool IsEmpty()
```

**F#**<br />
``` F#
static member IsEmpty : unit -> bool 

```


#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the clipboard is empty; otherwise, `false` (`False` in Visual Basic).

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ClipboardUtil">ClipboardUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />