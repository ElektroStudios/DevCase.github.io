# SystemNotificationUtil.NotifyFileRenamed Method 
 

Notifies the system that a file has been renamed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void NotifyFileRenamed(
	string oldFilePath,
	string newFilePath
)
```

**VB**<br />
``` VB
Public Shared Sub NotifyFileRenamed ( 
	oldFilePath As String,
	newFilePath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim oldFilePath As String
Dim newFilePath As StringSystemNotificationUtil.NotifyFileRenamed(oldFilePath, 
	newFilePath)
```

**C++**<br />
``` C++
public:
static void NotifyFileRenamed(
	String^ oldFilePath, 
	String^ newFilePath
)
```

**F#**<br />
``` F#
static member NotifyFileRenamed : 
        oldFilePath : string * 
        newFilePath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>oldFilePath</dt><dd>Type: System.String<br />The previous full path of the file that has been renamed.</dd><dt>newFilePath</dt><dd>Type: System.String<br />The new full path of the file that has been renamed.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>oldFilePath or newFilePath</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SystemNotificationUtil">SystemNotificationUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />