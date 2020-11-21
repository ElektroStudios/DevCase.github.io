# UserAccountUtil.CurrentUser Property 
 

Gets an UserPrincipal object that represents the current user.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static UserPrincipal CurrentUser { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CurrentUser As UserPrincipal
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As UserPrincipal

value = UserAccountUtil.CurrentUser

```

**C++**<br />
``` C++
public:
static property UserPrincipal^ CurrentUser {
	UserPrincipal^ get ();
}
```

**F#**<br />
``` F#
static member CurrentUser : UserPrincipal with get

```


#### Property Value
Type: UserPrincipal<br />An UserPrincipal object that represents the current user.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_UserAccountUtil">UserAccountUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />