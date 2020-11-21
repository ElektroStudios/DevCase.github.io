# SystemNotificationUtil.NotifyDirectoryAttributesChanged Method 
 

Notifies the system that the attributes of a directory have changed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void NotifyDirectoryAttributesChanged(
	string directoryPath
)
```

**VB**<br />
``` VB
Public Shared Sub NotifyDirectoryAttributesChanged ( 
	directoryPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim directoryPath As StringSystemNotificationUtil.NotifyDirectoryAttributesChanged(directoryPath)
```

**C++**<br />
``` C++
public:
static void NotifyDirectoryAttributesChanged(
	String^ directoryPath
)
```

**F#**<br />
``` F#
static member NotifyDirectoryAttributesChanged : 
        directoryPath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>directoryPath</dt><dd>Type: System.String<br />The full path of the directory on which its attributes has chaged.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>directoryPath</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SystemNotificationUtil">SystemNotificationUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />