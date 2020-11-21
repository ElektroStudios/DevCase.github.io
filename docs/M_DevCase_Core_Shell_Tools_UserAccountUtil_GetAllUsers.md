# UserAccountUtil.GetAllUsers Method 
 

Find and returns all the user accounts of the current machine context.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static List<UserPrincipal> GetAllUsers()
```

**VB**<br />
``` VB
Public Shared Function GetAllUsers As List(Of UserPrincipal)
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As List(Of UserPrincipal)

returnValue = UserAccountUtil.GetAllUsers()
```

**C++**<br />
``` C++
public:
static List<UserPrincipal^>^ GetAllUsers()
```

**F#**<br />
``` F#
static member GetAllUsers : unit -> List<UserPrincipal> 

```


#### Return Value
Type: List(UserPrincipal)<br />A List(T) collection that contains the users.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim users As List(Of UserPrincipal) = UserAccounts.GetAllUsers()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_UserAccountUtil">UserAccountUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />