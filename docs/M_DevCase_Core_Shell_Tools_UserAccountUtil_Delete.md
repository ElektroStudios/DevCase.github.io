# UserAccountUtil.Delete Method 
 

Deletes an user account in the current machine context.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Delete(
	string username
)
```

**VB**<br />
``` VB
Public Shared Sub Delete ( 
	username As String
)
```

**VB Usage**<br />
``` VB Usage
Dim username As StringUserAccountUtil.Delete(username)
```

**C++**<br />
``` C++
public:
static void Delete(
	String^ username
)
```

**F#**<br />
``` F#
static member Delete : 
        username : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>username</dt><dd>Type: System.String<br />The user name of the user-account to delete.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
UserAccounts.Delete(username:="User name")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_UserAccountUtil">UserAccountUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />