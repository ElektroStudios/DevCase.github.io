# AppOpenWithInfo.FriendlyAppName Property 
 

Gets or sets the localizable name to display for an application instead of just the version information appearing, which may not be localizable. 

 The association query ASSOCSTR reads this registry entry value and falls back to use the FileDescription name in the version information. If that name is missing, the association query defaults to the display name of the file. 

 Applications should use ASSOCSTR_FRIENDLYAPPNAME to retrieve this information to obtain the proper behavior.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string FriendlyAppName { get; set; }
```

**VB**<br />
``` VB
Public Property FriendlyAppName As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppOpenWithInfo
Dim value As String

value = instance.FriendlyAppName

instance.FriendlyAppName = value
```

**C++**<br />
``` C++
public:
property String^ FriendlyAppName {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member FriendlyAppName : string with get, set

```


#### Property Value
Type: String<br />The localizable name to display for the application.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppOpenWithInfo">AppOpenWithInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />