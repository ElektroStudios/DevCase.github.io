# AppUtil.AppShellExecuteRegister Method 
 

Registers an application for `ShellExecute` features through `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\App Paths` registry subkey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void AppShellExecuteRegister(
	AppShellExecuteInfo info
)
```

**VB**<br />
``` VB
Public Shared Sub AppShellExecuteRegister ( 
	info As AppShellExecuteInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim info As AppShellExecuteInfoAppUtil.AppShellExecuteRegister(info)
```

**C++**<br />
``` C++
public:
static void AppShellExecuteRegister(
	AppShellExecuteInfo^ info
)
```

**F#**<br />
``` F#
static member AppShellExecuteRegister : 
        info : AppShellExecuteInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>info</dt><dd>Type: <a href="T_DevCase_Core_Application_AppShellExecuteInfo">DevCase.Core.Application.AppShellExecuteInfo</a><br />The application specific information for `OpenWith` registration.</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ee872121%28v=vs.85%29.aspx#appPaths" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ee872121%28v=vs.85%29.aspx#appPaths</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\Program Files\MyApplication.exe")
Dim info As New AppShellExecuteInfo(file)

With info
    .Path = String.Format("{0}\", file.DirectoryName)
    .DropTarget = Guid.Empty
    .UseUrl = False
    .DontUseDesktopChangeRouter = False
    .SupportedProtocols = String.Empty
End With

AppShellExecuteRegister(info)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />