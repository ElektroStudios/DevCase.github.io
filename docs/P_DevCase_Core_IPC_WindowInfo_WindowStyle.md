# WindowInfo.WindowStyle Property 
 

Gets or sets the window style.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC">DevCase.Core.IPC</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public WindowStyles WindowStyle { get; set; }
```

**VB**<br />
``` VB
Public Property WindowStyle As WindowStyles
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowInfo
Dim value As WindowStyles

value = instance.WindowStyle

instance.WindowStyle = value
```

**C++**<br />
``` C++
public:
property WindowStyles WindowStyle {
	WindowStyles get ();
	void set (WindowStyles value);
}
```

**F#**<br />
``` F#
member WindowStyle : WindowStyles with get, set

```


#### Property Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowStyles">WindowStyles</a><br />\[Missing <value> documentation for "P:DevCase.Core.IPC.WindowInfo.WindowStyle"\]

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_WindowInfo">WindowInfo Class</a><br /><a href="N_DevCase_Core_IPC">DevCase.Core.IPC Namespace</a><br />