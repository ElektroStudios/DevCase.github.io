# SystemNotificationUtil.NotifyDriveRemoved Method 
 

Notifies the system that a drive has been removed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void NotifyDriveRemoved(
	string driveRootPath
)
```

**VB**<br />
``` VB
Public Shared Sub NotifyDriveRemoved ( 
	driveRootPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim driveRootPath As StringSystemNotificationUtil.NotifyDriveRemoved(driveRootPath)
```

**C++**<br />
``` C++
public:
static void NotifyDriveRemoved(
	String^ driveRootPath
)
```

**F#**<br />
``` F#
static member NotifyDriveRemoved : 
        driveRootPath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>driveRootPath</dt><dd>Type: System.String<br />The root path of the drive that has been removed.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>driveRootPath</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SystemNotificationUtil">SystemNotificationUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />