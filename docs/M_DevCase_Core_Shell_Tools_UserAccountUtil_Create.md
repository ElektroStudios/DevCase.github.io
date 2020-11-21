# UserAccountUtil.Create Method 
 

Creates a new user account in the current machine context. This function does NOT adds a new user in the current machine.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static UserPrincipal Create(
	string username,
	string password,
	string displayName,
	string description,
	bool canChangePwd,
	bool pwdExpires
)
```

**VB**<br />
``` VB
Public Shared Function Create ( 
	username As String,
	password As String,
	displayName As String,
	description As String,
	canChangePwd As Boolean,
	pwdExpires As Boolean
) As UserPrincipal
```

**VB Usage**<br />
``` VB Usage
Dim username As String
Dim password As String
Dim displayName As String
Dim description As String
Dim canChangePwd As Boolean
Dim pwdExpires As Boolean
Dim returnValue As UserPrincipal

returnValue = UserAccountUtil.Create(username, 
	password, displayName, description, 
	canChangePwd, pwdExpires)
```

**C++**<br />
``` C++
public:
static UserPrincipal^ Create(
	String^ username, 
	String^ password, 
	String^ displayName, 
	String^ description, 
	bool canChangePwd, 
	bool pwdExpires
)
```

**F#**<br />
``` F#
static member Create : 
        username : string * 
        password : string * 
        displayName : string * 
        description : string * 
        canChangePwd : bool * 
        pwdExpires : bool -> UserPrincipal 

```


#### Parameters
&nbsp;<dl><dt>username</dt><dd>Type: System.String<br />The user name.</dd><dt>password</dt><dd>Type: System.String<br />The user password. If this value is empty, account is set to don't require any password.</dd><dt>displayName</dt><dd>Type: System.String<br />The display name of the user account.</dd><dt>description</dt><dd>Type: System.String<br />The description of the user account.</dd><dt>canChangePwd</dt><dd>Type: System.Boolean<br />A value that indicates whether the user can change its password.</dd><dt>pwdExpires</dt><dd>Type: System.Boolean<br />A value that indicates whether the password should expire.</dd></dl>

#### Return Value
Type: UserPrincipal<br />An UserPrincipal object that contains the user data.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim user as UserPrincipal = UserAccounts.Create(username:="Elektro",
                                                   password:="",
                                                   displayName:="Elektro Account.",
                                                   description:="This is a test user-account.",
                                                   canChangePwd:=True,
                                                   pwdExpires:=False,
                                                   groupSid:=WellKnownSidType.BuiltinAdministratorsSid)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_UserAccountUtil">UserAccountUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />