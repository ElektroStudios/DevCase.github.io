# UIAutomationUtil.WaitForWindow Method (String, String, TimeSpan)
 

Waits the specified amount of time for a top-level window to be shown in the screen, whose class name and window title matches the specified parameters.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IntPtr WaitForWindow(
	string className,
	string title,
	TimeSpan timeout
)
```

**VB**<br />
``` VB
Public Shared Function WaitForWindow ( 
	className As String,
	title As String,
	timeout As TimeSpan
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim className As String
Dim title As String
Dim timeout As TimeSpan
Dim returnValue As IntPtr

returnValue = UIAutomationUtil.WaitForWindow(className, 
	title, timeout)
```

**C++**<br />
``` C++
public:
static IntPtr WaitForWindow(
	String^ className, 
	String^ title, 
	TimeSpan timeout
)
```

**F#**<br />
``` F#
static member WaitForWindow : 
        className : string * 
        title : string * 
        timeout : TimeSpan -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>className</dt><dd>Type: System.String<br />The window class name.</dd><dt>title</dt><dd>Type: System.String<br />The window title. This value can be String.</dd><dt>timeout</dt><dd>Type: System.TimeSpan<br />The timeout interval, in milliseconds.</dd></dl>

#### Return Value
Type: IntPtr<br />A handle to the top-level window whose class name and window name matches the specified parameters. 

 Returns Zero if the window is not found between the specified timeout interval.

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_WaitForWindow">WaitForWindow Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />