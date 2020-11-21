# MouseMonitor Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_MouseMonitor">MouseMonitor</a> class. 

 Caling this constructor causes to registers the raw input devices for the calling window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MouseMonitor(
	IWin32Window window
)
```

**VB**<br />
``` VB
Public Sub New ( 
	window As IWin32Window
)
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window

Dim instance As New MouseMonitor(window)
```

**C++**<br />
``` C++
public:
MouseMonitor(
	IWin32Window^ window
)
```

**F#**<br />
``` F#
new : 
        window : IWin32Window -> MouseMonitor
```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The window that will listen for device events.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ApplicationException</td><td>Failed to register raw input device(s).</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MouseMonitor">MouseMonitor Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />