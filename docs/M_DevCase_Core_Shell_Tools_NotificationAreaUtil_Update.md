# NotificationAreaUtil.Update Method 
 

Updates (redraw) the bounds of the visible section of the notification area window. 

 You should call this method if there are dummy (non-functional) buttons from applications that terminated abruptly, or if you did modifications, like for example a button removal through <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ToolbarMessages">DeleteButton</a> message.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Update()
```

**VB**<br />
``` VB
Public Shared Sub Update
```

**VB Usage**<br />
``` VB Usage

NotificationAreaUtil.Update()
```

**C++**<br />
``` C++
public:
static void Update()
```

**F#**<br />
``` F#
static member Update : unit -> unit 

```


## Remarks
<a href="https://stackoverflow.com/a/55733696/1248295" target="_blank">https://stackoverflow.com/a/55733696/1248295</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_NotificationAreaUtil">NotificationAreaUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />