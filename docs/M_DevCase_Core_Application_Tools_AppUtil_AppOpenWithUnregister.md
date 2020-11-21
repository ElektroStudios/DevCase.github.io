# AppUtil.AppOpenWithUnregister Method 
 

Unregisters an application that has been registered for `OpenWith` features using the <a href="M_DevCase_Core_Application_Tools_AppUtil_AppOpenWithRegister">AppOpenWithRegister(AppOpenWithInfo)</a> method.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void AppOpenWithUnregister(
	AppOpenWithInfo info
)
```

**VB**<br />
``` VB
Public Shared Sub AppOpenWithUnregister ( 
	info As AppOpenWithInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim info As AppOpenWithInfoAppUtil.AppOpenWithUnregister(info)
```

**C++**<br />
``` C++
public:
static void AppOpenWithUnregister(
	AppOpenWithInfo^ info
)
```

**F#**<br />
``` F#
static member AppOpenWithUnregister : 
        info : AppOpenWithInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>info</dt><dd>Type: <a href="T_DevCase_Core_Application_AppOpenWithInfo">DevCase.Core.Application.AppOpenWithInfo</a><br />The application specific information for `OpenWith` unregistration.</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ee872121%28v=vs.85%29.aspx#applications" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ee872121%28v=vs.85%29.aspx#applications</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\Program Files\MyApplication.exe")
Dim info As New AppOpenWithInfo(file)

AppUtil.AppOpenWithUnregister(info)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />