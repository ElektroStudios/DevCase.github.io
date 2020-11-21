# AppUtil.AppOpenWithRegister Method 
 

Registers an application for `OpenWith` features through the `HKEY_CLASSES_ROOT\Applications\ApplicationName.exe` registry subkey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void AppOpenWithRegister(
	AppOpenWithInfo info
)
```

**VB**<br />
``` VB
Public Shared Sub AppOpenWithRegister ( 
	info As AppOpenWithInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim info As AppOpenWithInfoAppUtil.AppOpenWithRegister(info)
```

**C++**<br />
``` C++
public:
static void AppOpenWithRegister(
	AppOpenWithInfo^ info
)
```

**F#**<br />
``` F#
static member AppOpenWithRegister : 
        info : AppOpenWithInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>info</dt><dd>Type: <a href="T_DevCase_Core_Application_AppOpenWithInfo">DevCase.Core.Application.AppOpenWithInfo</a><br />The application specific information for `OpenWith` registration.</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ee872121%28v=vs.85%29.aspx#applications" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ee872121%28v=vs.85%29.aspx#applications</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\Program Files\MyApplication.exe")
Dim info As New AppOpenWithInfo(file)

With info
    .FriendlyAppName = Path.GetFileNameWithoutExtension(file.Name)
    .Verb = String.Format("""{0}"" ""%1""", file.FullName)
    .DefaultIcon = String.Format("""{0}"",0", file.FullName)
    .TaskbarGroupIcon = info.DefaultIcon
    .SupportedTypes = {".mp2", ".mp3"}
    .IsHostApp = False
    .NoOpenWith = False
    .NoStartPage = False
    .UseExecutableForTaskbarGroupIcon = False
End With

AppUtil.AppOpenWithRegister(info)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />