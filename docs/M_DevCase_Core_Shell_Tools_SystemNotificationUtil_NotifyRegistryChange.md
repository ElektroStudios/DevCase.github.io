# SystemNotificationUtil.NotifyRegistryChange Method 
 

Notifies the system to update after a registry change.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void NotifyRegistryChange(
	string keyName
)
```

**VB**<br />
``` VB
Public Shared Sub NotifyRegistryChange ( 
	keyName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim keyName As StringSystemNotificationUtil.NotifyRegistryChange(keyName)
```

**C++**<br />
``` C++
public:
static void NotifyRegistryChange(
	String^ keyName
)
```

**F#**<br />
``` F#
static member NotifyRegistryChange : 
        keyName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>keyName</dt><dd>Type: System.String<br />A string that indicates the area containing the system parameter that was changed. This string can be the name of a registry key or the name of a section in the Win.ini file. When the string is a registry name, it typically indicates only the leaf node in the registry, not the full path. To effect a change in the policy settings, this parameter points to the string "Policy". To effect a change in the locale settings, this parameter points to the string "intl". To effect a change in the environment variables for the system or the user, this parameter points to the string "Environment".</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms725497%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms725497%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SystemNotificationUtil">SystemNotificationUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />