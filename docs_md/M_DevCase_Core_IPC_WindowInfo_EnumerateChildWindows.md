# WindowInfo.EnumerateChildWindows Method 
 

Enumerates the child windows of this window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC">DevCase.Core.IPC</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IEnumerable<WindowInfo> EnumerateChildWindows()
```

**VB**<br />
``` VB
Public Function EnumerateChildWindows As IEnumerable(Of WindowInfo)
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowInfo
Dim returnValue As IEnumerable(Of WindowInfo)

returnValue = instance.EnumerateChildWindows()
```

**C++**<br />
``` C++
public:
IEnumerable<WindowInfo^>^ EnumerateChildWindows()
```

**F#**<br />
``` F#
member EnumerateChildWindows : unit -> IEnumerable<WindowInfo> 

```


#### Return Value
Type: IEnumerable(<a href="T_DevCase_Core_IPC_WindowInfo">WindowInfo</a>)<br />The child windows of this window.

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_WindowInfo">WindowInfo Class</a><br /><a href="N_DevCase_Core_IPC">DevCase.Core.IPC Namespace</a><br />