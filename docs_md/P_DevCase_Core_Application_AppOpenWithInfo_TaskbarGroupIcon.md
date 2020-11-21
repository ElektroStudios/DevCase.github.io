# AppOpenWithInfo.TaskbarGroupIcon Property 
 

Gets or sets the icon used to override the taskbar icon. The window icon is normally used for the taskbar. 

 Setting the TaskbarGroupIcon entry causes the system to use the icon from the .exe for the application instead.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string TaskbarGroupIcon { get; set; }
```

**VB**<br />
``` VB
Public Property TaskbarGroupIcon As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppOpenWithInfo
Dim value As String

value = instance.TaskbarGroupIcon

instance.TaskbarGroupIcon = value
```

**C++**<br />
``` C++
public:
property String^ TaskbarGroupIcon {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member TaskbarGroupIcon : string with get, set

```


#### Property Value
Type: String<br />The taskbar group icon.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppOpenWithInfo">AppOpenWithInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />