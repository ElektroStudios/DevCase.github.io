# UserAccountUtil.FindUser Method (String)
 

Finds an user account that matches the specified name in the current machine context.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static UserPrincipal FindUser(
	string username
)
```

**VB**<br />
``` VB
Public Shared Function FindUser ( 
	username As String
) As UserPrincipal
```

**VB Usage**<br />
``` VB Usage
Dim username As String
Dim returnValue As UserPrincipal

returnValue = UserAccountUtil.FindUser(username)
```

**C++**<br />
``` C++
public:
static UserPrincipal^ FindUser(
	String^ username
)
```

**F#**<br />
``` F#
static member FindUser : 
        username : string -> UserPrincipal 

```


#### Parameters
&nbsp;<dl><dt>username</dt><dd>Type: System.String<br />The user name to find.</dd></dl>

#### Return Value
Type: UserPrincipal<br />An UserPrincipal object that contains the user data.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>User not found.;username</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim user As UserPrincipal = UserAccounts.FindUser(username:="Administrator")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_UserAccountUtil">UserAccountUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_UserAccountUtil_FindUser">FindUser Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />