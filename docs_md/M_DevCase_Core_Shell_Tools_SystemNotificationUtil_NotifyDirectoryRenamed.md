# SystemNotificationUtil.NotifyDirectoryRenamed Method 
 

Notifies the system that a directory has been renamed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void NotifyDirectoryRenamed(
	string oldDirectoryPath,
	string newDirectoryPath
)
```

**VB**<br />
``` VB
Public Shared Sub NotifyDirectoryRenamed ( 
	oldDirectoryPath As String,
	newDirectoryPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim oldDirectoryPath As String
Dim newDirectoryPath As StringSystemNotificationUtil.NotifyDirectoryRenamed(oldDirectoryPath, 
	newDirectoryPath)
```

**C++**<br />
``` C++
public:
static void NotifyDirectoryRenamed(
	String^ oldDirectoryPath, 
	String^ newDirectoryPath
)
```

**F#**<br />
``` F#
static member NotifyDirectoryRenamed : 
        oldDirectoryPath : string * 
        newDirectoryPath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>oldDirectoryPath</dt><dd>Type: System.String<br />The previous full path of the directory that has been renamed.</dd><dt>newDirectoryPath</dt><dd>Type: System.String<br />The new full path of the directory that has been renamed.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>oldDirectoryPath or newDirectoryPath</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SystemNotificationUtil">SystemNotificationUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />