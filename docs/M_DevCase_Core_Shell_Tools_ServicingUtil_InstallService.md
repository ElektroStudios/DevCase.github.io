# ServicingUtil.InstallService Method 
 

Installs a service.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void InstallService(
	string filepath,
	string svcName,
	string displayName = "",
	string description = "",
	ServiceStartMode startType = ServiceStartMode.Automatic,
	ServiceAccount account = ServiceAccount.LocalSystem,
	string username = "",
	string password = ""
)
```

**VB**<br />
``` VB
Public Shared Sub InstallService ( 
	filepath As String,
	svcName As String,
	Optional displayName As String = "",
	Optional description As String = "",
	Optional startType As ServiceStartMode = ServiceStartMode.Automatic,
	Optional account As ServiceAccount = ServiceAccount.LocalSystem,
	Optional username As String = "",
	Optional password As String = ""
)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim svcName As String
Dim displayName As String
Dim description As String
Dim startType As ServiceStartMode
Dim account As ServiceAccount
Dim username As String
Dim password As StringServicingUtil.InstallService(filepath, svcName, 
	displayName, description, startType, 
	account, username, password)
```

**C++**<br />
``` C++
public:
static void InstallService(
	String^ filepath, 
	String^ svcName, 
	String^ displayName = L"", 
	String^ description = L"", 
	ServiceStartMode startType = ServiceStartMode::Automatic, 
	ServiceAccount account = ServiceAccount::LocalSystem, 
	String^ username = L"", 
	String^ password = L""
)
```

**F#**<br />
``` F#
static member InstallService : 
        filepath : string * 
        svcName : string * 
        ?displayName : string * 
        ?description : string * 
        ?startType : ServiceStartMode * 
        ?account : ServiceAccount * 
        ?username : string * 
        ?password : string 
(* Defaults:
        let _displayName = defaultArg displayName ""
        let _description = defaultArg description ""
        let _startType = defaultArg startType ServiceStartMode.Automatic
        let _account = defaultArg account ServiceAccount.LocalSystem
        let _username = defaultArg username ""
        let _password = defaultArg password ""
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The service filepath.</dd><dt>svcName</dt><dd>Type: System.String<br />The service name.</dd><dt>displayName (Optional)</dt><dd>Type: System.String<br />The service display name.</dd><dt>description (Optional)</dt><dd>Type: System.String<br />The service description.</dd><dt>startType (Optional)</dt><dd>Type: System.ServiceProcess.ServiceStartMode<br />The service start type.</dd><dt>account (Optional)</dt><dd>Type: System.ServiceProcess.ServiceAccount<br />The service account.</dd><dt>username (Optional)</dt><dd>Type: System.String<br />The service username.</dd><dt>password (Optional)</dt><dd>Type: System.String<br />The username password.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ServicingUtil">ServicingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />