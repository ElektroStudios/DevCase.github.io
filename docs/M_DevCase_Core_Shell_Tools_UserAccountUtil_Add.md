# UserAccountUtil.Add Method (UserPrincipal, WellKnownSidType)
 

Adds a new user account in the current machine context.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Add(
	UserPrincipal user,
	WellKnownSidType groupSid = 27
)
```

**VB**<br />
``` VB
Public Shared Sub Add ( 
	user As UserPrincipal,
	Optional groupSid As WellKnownSidType = 27
)
```

**VB Usage**<br />
``` VB Usage
Dim user As UserPrincipal
Dim groupSid As WellKnownSidTypeUserAccountUtil.Add(user, groupSid)
```

**C++**<br />
``` C++
public:
static void Add(
	UserPrincipal^ user, 
	WellKnownSidType groupSid = 27
)
```

**F#**<br />
``` F#
static member Add : 
        user : UserPrincipal * 
        ?groupSid : WellKnownSidType 
(* Defaults:
        let _groupSid = defaultArg groupSid 27
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>user</dt><dd>Type: System.DirectoryServices.AccountManagement.UserPrincipal<br />An UserPrincipal object that contains the user data.</dd><dt>groupSid (Optional)</dt><dd>Type: System.Security.Principal.WellKnownSidType<br />A WellKnownSidType security identifier (SID) that determines the account group where to add the user.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
UserAccounts.Add(user:=myUserPrincipal, groupSid:=WellKnownSidType.BuiltinAdministratorsSid)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_UserAccountUtil">UserAccountUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_UserAccountUtil_Add">Add Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />