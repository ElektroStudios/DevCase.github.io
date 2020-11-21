# SystemNotificationUtil.NotifyDriveAdded Method 
 

Notifies the system that a drive has been added.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void NotifyDriveAdded(
	string driveRootPath,
	bool createShellWindow = false
)
```

**VB**<br />
``` VB
Public Shared Sub NotifyDriveAdded ( 
	driveRootPath As String,
	Optional createShellWindow As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim driveRootPath As String
Dim createShellWindow As BooleanSystemNotificationUtil.NotifyDriveAdded(driveRootPath, 
	createShellWindow)
```

**C++**<br />
``` C++
public:
static void NotifyDriveAdded(
	String^ driveRootPath, 
	bool createShellWindow = false
)
```

**F#**<br />
``` F#
static member NotifyDriveAdded : 
        driveRootPath : string * 
        ?createShellWindow : bool 
(* Defaults:
        let _createShellWindow = defaultArg createShellWindow false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>driveRootPath</dt><dd>Type: System.String<br />The root path of the drive that has been added.</dd><dt>createShellWindow (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), tell the Shell to create a new window for the drive.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>driveRootPath</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SystemNotificationUtil">SystemNotificationUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />