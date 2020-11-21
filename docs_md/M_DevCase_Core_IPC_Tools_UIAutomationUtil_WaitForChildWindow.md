# UIAutomationUtil.WaitForChildWindow Method (IntPtr, String, String, Double)
 

Waits the specified amount of time for a child window to be shown in the screen, whose class name and window title matches the specified parameters.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IntPtr WaitForChildWindow(
	IntPtr parentWindow,
	string className,
	string title,
	double timeout
)
```

**VB**<br />
``` VB
Public Shared Function WaitForChildWindow ( 
	parentWindow As IntPtr,
	className As String,
	title As String,
	timeout As Double
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim parentWindow As IntPtr
Dim className As String
Dim title As String
Dim timeout As Double
Dim returnValue As IntPtr

returnValue = UIAutomationUtil.WaitForChildWindow(parentWindow, 
	className, title, timeout)
```

**C++**<br />
``` C++
public:
static IntPtr WaitForChildWindow(
	IntPtr parentWindow, 
	String^ className, 
	String^ title, 
	double timeout
)
```

**F#**<br />
``` F#
static member WaitForChildWindow : 
        parentWindow : IntPtr * 
        className : string * 
        title : string * 
        timeout : float -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>parentWindow</dt><dd>Type: System.IntPtr<br />A handle to the parent window.</dd><dt>className</dt><dd>Type: System.String<br />The window class name.</dd><dt>title</dt><dd>Type: System.String<br />The window title. This value can be String.</dd><dt>timeout</dt><dd>Type: System.Double<br />The timeout interval, in milliseconds. This value can be Infinite.</dd></dl>

#### Return Value
Type: IntPtr<br />A handle to the child window whose class name and window name matches the specified parameters. 

 Returns Zero if the window is not found between the specified timeout interval.

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_WaitForChildWindow">WaitForChildWindow Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />