# UserAccountUtil.IsMemberOfGroup Method (String, String)
 

Determines whether an user-account of the current machine context is a member of the specified group.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsMemberOfGroup(
	string username,
	string groupname
)
```

**VB**<br />
``` VB
Public Shared Function IsMemberOfGroup ( 
	username As String,
	groupname As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim username As String
Dim groupname As String
Dim returnValue As Boolean

returnValue = UserAccountUtil.IsMemberOfGroup(username, 
	groupname)
```

**C++**<br />
``` C++
public:
static bool IsMemberOfGroup(
	String^ username, 
	String^ groupname
)
```

**F#**<br />
``` F#
static member IsMemberOfGroup : 
        username : string * 
        groupname : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>username</dt><dd>Type: System.String<br />The user name.</dd><dt>groupname</dt><dd>Type: System.String<br />The name of thehe group.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the user is a member of the specified group, otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim userIsGuest As Boolean = UserAccounts.IsMemberOfGroup(username:="Administrator", groupname:="Guests")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_UserAccountUtil">UserAccountUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_UserAccountUtil_IsMemberOfGroup">IsMemberOfGroup Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />