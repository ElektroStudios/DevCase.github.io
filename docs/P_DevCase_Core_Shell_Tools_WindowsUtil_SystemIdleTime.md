# WindowsUtil.SystemIdleTime Property 
 

Retrieves the time of the last input (mouse or keyboard) event in the operating system. That is, the last time the user has pressed a key or used the mouse.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static TimeSpan SystemIdleTime { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property SystemIdleTime As TimeSpan
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As TimeSpan

value = WindowsUtil.SystemIdleTime

```

**C++**<br />
``` C++
public:
static property TimeSpan SystemIdleTime {
	TimeSpan get ();
}
```

**F#**<br />
``` F#
static member SystemIdleTime : TimeSpan with get

```


#### Property Value
Type: TimeSpan<br />The time of the last input (mouse or keyboard) event in the operating system.

## Examples
This is a code example. 
**VB**<br />
``` VB
Do While True
    Label1.Text = SystemIdleTime.ToString("dd\.hh\:mm\:ss\:fff") ' Days.Hours:Minutes:Seconds:Milliseconds
    Thread.Sleep(50)
    Application.DoEvents()
Loop
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_WindowsUtil">WindowsUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />