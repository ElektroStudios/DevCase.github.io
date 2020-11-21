# GraphicalUtil.GetNotifyIconRect Method 
 

Gets the screen coordinates of the bounding Rectangle of the specified NotifyIcon.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Rectangle GetNotifyIconRect(
	NotifyIcon ntfy
)
```

**VB**<br />
``` VB
Public Shared Function GetNotifyIconRect ( 
	ntfy As NotifyIcon
) As Rectangle
```

**VB Usage**<br />
``` VB Usage
Dim ntfy As NotifyIcon
Dim returnValue As Rectangle

returnValue = GraphicalUtil.GetNotifyIconRect(ntfy)
```

**C++**<br />
``` C++
public:
static Rectangle GetNotifyIconRect(
	NotifyIcon^ ntfy
)
```

**F#**<br />
``` F#
static member GetNotifyIconRect : 
        ntfy : NotifyIcon -> Rectangle 

```


#### Parameters
&nbsp;<dl><dt>ntfy</dt><dd>Type: System.Windows.Forms.NotifyIcon<br />The source NotifyIcon.</dd></dl>

#### Return Value
Type: Rectangle<br />The Rectangle of the source NotifyIcon.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim ntfyRect As Rectangle = GetNotifyIconRect(Me.NotifyIcon1)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />