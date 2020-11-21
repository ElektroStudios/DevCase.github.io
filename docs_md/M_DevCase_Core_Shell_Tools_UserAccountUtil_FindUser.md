# UserAccountUtil.FindUser Method (SecurityIdentifier)
 

Finds an user account that matches the specified security identifier (SID) in the current machine context.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static UserPrincipal FindUser(
	SecurityIdentifier sid
)
```

**VB**<br />
``` VB
Public Shared Function FindUser ( 
	sid As SecurityIdentifier
) As UserPrincipal
```

**VB Usage**<br />
``` VB Usage
Dim sid As SecurityIdentifier
Dim returnValue As UserPrincipal

returnValue = UserAccountUtil.FindUser(sid)
```

**C++**<br />
``` C++
public:
static UserPrincipal^ FindUser(
	SecurityIdentifier^ sid
)
```

**F#**<br />
``` F#
static member FindUser : 
        sid : SecurityIdentifier -> UserPrincipal 

```


#### Parameters
&nbsp;<dl><dt>sid</dt><dd>Type: System.Security.Principal.SecurityIdentifier<br />A SecurityIdentifier (SID) object.</dd></dl>

#### Return Value
Type: UserPrincipal<br />An UserPrincipal object that contains the user data.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>User not found.;username</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim user As UserPrincipal = UserAccounts.FindUser(sid:=New SecurityIdentifier("S-1-5-21-1780771175-1208154119-2269826705-500"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_UserAccountUtil">UserAccountUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_UserAccountUtil_FindUser">FindUser Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />