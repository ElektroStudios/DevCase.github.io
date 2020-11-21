# GraphicalUtil.GetNotifyIconHandle Method 
 

Gets the handle of the specified NotifyIcon.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IntPtr GetNotifyIconHandle(
	NotifyIcon ntfy
)
```

**VB**<br />
``` VB
Public Shared Function GetNotifyIconHandle ( 
	ntfy As NotifyIcon
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim ntfy As NotifyIcon
Dim returnValue As IntPtr

returnValue = GraphicalUtil.GetNotifyIconHandle(ntfy)
```

**C++**<br />
``` C++
public:
static IntPtr GetNotifyIconHandle(
	NotifyIcon^ ntfy
)
```

**F#**<br />
``` F#
static member GetNotifyIconHandle : 
        ntfy : NotifyIcon -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>ntfy</dt><dd>Type: System.Windows.Forms.NotifyIcon<br />The source NotifyIcon.</dd></dl>

#### Return Value
Type: IntPtr<br />The handle of the source NotifyIcon.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim handle As IntPtr = GetNotifyIconHandle(Me.NotifyIcon1)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />