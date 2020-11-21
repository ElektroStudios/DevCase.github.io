# WindowInfo.IsChild Method 
 

Determines whether this window is a child window or descendant window of a specified parent window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC">DevCase.Core.IPC</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool IsChild(
	IntPtr hWnd
)
```

**VB**<br />
``` VB
Public Function IsChild ( 
	hWnd As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowInfo
Dim hWnd As IntPtr
Dim returnValue As Boolean

returnValue = instance.IsChild(hWnd)
```

**C++**<br />
``` C++
public:
bool IsChild(
	IntPtr hWnd
)
```

**F#**<br />
``` F#
member IsChild : 
        hWnd : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the parent window.</dd></dl>

#### Return Value
Type: Boolean<br />\[Missing <returns> documentation for "M:DevCase.Core.IPC.WindowInfo.IsChild(System.IntPtr)"\]

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_WindowInfo">WindowInfo Class</a><br /><a href="N_DevCase_Core_IPC">DevCase.Core.IPC Namespace</a><br />