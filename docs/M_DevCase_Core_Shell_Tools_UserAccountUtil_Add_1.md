# UserAccountUtil.Add Method (String, String, String, String, Boolean, Boolean, WellKnownSidType)
 

Adds a new user account in the current machine context.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Add(
	string username,
	string password,
	string displayName,
	string description,
	bool canChangePwd,
	bool pwdExpires,
	WellKnownSidType groupSid = 27
)
```

**VB**<br />
``` VB
Public Shared Sub Add ( 
	username As String,
	password As String,
	displayName As String,
	description As String,
	canChangePwd As Boolean,
	pwdExpires As Boolean,
	Optional groupSid As WellKnownSidType = 27
)
```

**VB Usage**<br />
``` VB Usage
Dim username As String
Dim password As String
Dim displayName As String
Dim description As String
Dim canChangePwd As Boolean
Dim pwdExpires As Boolean
Dim groupSid As WellKnownSidTypeUserAccountUtil.Add(username, password, displayName, 
	description, canChangePwd, pwdExpires, 
	groupSid)
```

**C++**<br />
``` C++
public:
static void Add(
	String^ username, 
	String^ password, 
	String^ displayName, 
	String^ description, 
	bool canChangePwd, 
	bool pwdExpires, 
	WellKnownSidType groupSid = 27
)
```

**F#**<br />
``` F#
static member Add : 
        username : string * 
        password : string * 
        displayName : string * 
        description : string * 
        canChangePwd : bool * 
        pwdExpires : bool * 
        ?groupSid : WellKnownSidType 
(* Defaults:
        let _groupSid = defaultArg groupSid 27
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>username</dt><dd>Type: System.String<br />The user name.</dd><dt>password</dt><dd>Type: System.String<br />The user password. If this value is empty, account is set to don't require any password.</dd><dt>displayName</dt><dd>Type: System.String<br />The display name of the user account.</dd><dt>description</dt><dd>Type: System.String<br />The description of the user account.</dd><dt>canChangePwd</dt><dd>Type: System.Boolean<br />A value that indicates whether the user can change its password.</dd><dt>pwdExpires</dt><dd>Type: System.Boolean<br />A value that indicates whether the password should expire.</dd><dt>groupSid (Optional)</dt><dd>Type: System.Security.Principal.WellKnownSidType<br />A WellKnownSidType security identifier (SID) that determines the account group where to add the user.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
UserAccounts.Add(username:="Elektro",
                    password:="",
                    displayName:="Elektro Account.",
                    description:="This is a test user-account.",
                    canChangePwd:=True,
                    pwdExpires:=False,
                    groupSid:=WellKnownSidType.BuiltinAdministratorsSid)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_UserAccountUtil">UserAccountUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_UserAccountUtil_Add">Add Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />