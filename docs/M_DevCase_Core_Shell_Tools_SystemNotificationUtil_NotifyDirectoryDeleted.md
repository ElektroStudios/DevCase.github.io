# SystemNotificationUtil.NotifyDirectoryDeleted Method 
 

Notifies the system that a directory has been deleted.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void NotifyDirectoryDeleted(
	string directoryPath
)
```

**VB**<br />
``` VB
Public Shared Sub NotifyDirectoryDeleted ( 
	directoryPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim directoryPath As StringSystemNotificationUtil.NotifyDirectoryDeleted(directoryPath)
```

**C++**<br />
``` C++
public:
static void NotifyDirectoryDeleted(
	String^ directoryPath
)
```

**F#**<br />
``` F#
static member NotifyDirectoryDeleted : 
        directoryPath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>directoryPath</dt><dd>Type: System.String<br />The full path of the directory that has been deleted.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>directoryPath</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SystemNotificationUtil">SystemNotificationUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />