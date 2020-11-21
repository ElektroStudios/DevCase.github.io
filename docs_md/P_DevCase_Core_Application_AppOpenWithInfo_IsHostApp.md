# AppOpenWithInfo.IsHostApp Property 
 

Gets or sets a value indicating whether the process is a host process, such as Rundll32.exe or Dllhost.exe, and should not be considered for Start menu pinning or inclusion in the Most Frequently Used (MFU) list. 

 When launched with a shortcut that contains a non-null argument list or an explicit Application User Model IDs (AppUserModelIDs), the process can be pinned (as that shortcut). Such shortcuts are candidates for inclusion in the MFU list.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool IsHostApp { get; set; }
```

**VB**<br />
``` VB
Public Property IsHostApp As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppOpenWithInfo
Dim value As Boolean

value = instance.IsHostApp

instance.IsHostApp = value
```

**C++**<br />
``` C++
public:
property bool IsHostApp {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member IsHostApp : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the process is a host process; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppOpenWithInfo">AppOpenWithInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />