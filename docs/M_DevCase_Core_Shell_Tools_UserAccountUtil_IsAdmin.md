# UserAccountUtil.IsAdmin Method 
 

Determines whether an user-account of the current machine context is an Administrator.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsAdmin(
	string username
)
```

**VB**<br />
``` VB
Public Shared Function IsAdmin ( 
	username As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim username As String
Dim returnValue As Boolean

returnValue = UserAccountUtil.IsAdmin(username)
```

**C++**<br />
``` C++
public:
static bool IsAdmin(
	String^ username
)
```

**F#**<br />
``` F#
static member IsAdmin : 
        username : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>username</dt><dd>Type: System.String<br />The user name.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the user is an Administrator, otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim userIsAdmin As Boolean = UserAccounts.IsAdmin(username:="Administrator")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_UserAccountUtil">UserAccountUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />