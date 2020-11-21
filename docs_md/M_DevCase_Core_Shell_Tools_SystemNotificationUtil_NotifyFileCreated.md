# SystemNotificationUtil.NotifyFileCreated Method 
 

Notifies the system that a file has been created.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void NotifyFileCreated(
	string filePath
)
```

**VB**<br />
``` VB
Public Shared Sub NotifyFileCreated ( 
	filePath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim filePath As StringSystemNotificationUtil.NotifyFileCreated(filePath)
```

**C++**<br />
``` C++
public:
static void NotifyFileCreated(
	String^ filePath
)
```

**F#**<br />
``` F#
static member NotifyFileCreated : 
        filePath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />The full path of the file that has been created.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>filePath</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SystemNotificationUtil">SystemNotificationUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />