# ServicingUtil.UninstallService Method 
 

Uninstalls a service.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void UninstallService(
	string svcName,
	ServiceAccount account = ServiceAccount.LocalSystem,
	string username = "",
	string password = ""
)
```

**VB**<br />
``` VB
Public Shared Sub UninstallService ( 
	svcName As String,
	Optional account As ServiceAccount = ServiceAccount.LocalSystem,
	Optional username As String = "",
	Optional password As String = ""
)
```

**VB Usage**<br />
``` VB Usage
Dim svcName As String
Dim account As ServiceAccount
Dim username As String
Dim password As StringServicingUtil.UninstallService(svcName, account, 
	username, password)
```

**C++**<br />
``` C++
public:
static void UninstallService(
	String^ svcName, 
	ServiceAccount account = ServiceAccount::LocalSystem, 
	String^ username = L"", 
	String^ password = L""
)
```

**F#**<br />
``` F#
static member UninstallService : 
        svcName : string * 
        ?account : ServiceAccount * 
        ?username : string * 
        ?password : string 
(* Defaults:
        let _account = defaultArg account ServiceAccount.LocalSystem
        let _username = defaultArg username ""
        let _password = defaultArg password ""
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>svcName</dt><dd>Type: System.String<br />The service name.</dd><dt>account (Optional)</dt><dd>Type: System.ServiceProcess.ServiceAccount<br />The service account.</dd><dt>username (Optional)</dt><dd>Type: System.String<br />The service username.</dd><dt>password (Optional)</dt><dd>Type: System.String<br />The username password.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ServicingUtil">ServicingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />