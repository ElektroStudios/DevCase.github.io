# GraphicalUtil.ShakeControl Method 
 

Shakes the window of a Control during the specified amount of time.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void ShakeControl(
	Control ctrl,
	int amplitudeFactor,
	TimeSpan timespan
)
```

**VB**<br />
``` VB
Public Sub ShakeControl ( 
	ctrl As Control,
	amplitudeFactor As Integer,
	timespan As TimeSpan
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As GraphicalUtil
Dim ctrl As Control
Dim amplitudeFactor As Integer
Dim timespan As TimeSpan

instance.ShakeControl(ctrl, amplitudeFactor, 
	timespan)
```

**C++**<br />
``` C++
public:
void ShakeControl(
	Control^ ctrl, 
	int amplitudeFactor, 
	TimeSpan timespan
)
```

**F#**<br />
``` F#
member ShakeControl : 
        ctrl : Control * 
        amplitudeFactor : int * 
        timespan : TimeSpan -> unit 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The Control to shake.</dd><dt>amplitudeFactor</dt><dd>Type: System.Int32<br />When bigger the value, bigger the effect amplitude. 

 Recommended value: 15</dd><dt>timespan</dt><dd>Type: System.TimeSpan<br />The amount of time the effect will last.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
ShakeForm(My.Forms.Form1, 15, TimeSpan.FromMilliseconds(200))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />