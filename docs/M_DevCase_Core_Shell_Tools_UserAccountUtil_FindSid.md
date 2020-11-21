# UserAccountUtil.FindSid Method 
 

Finds the security identifier (SID) of the specified username account in the current machine context.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static SecurityIdentifier FindSid(
	string username
)
```

**VB**<br />
``` VB
Public Shared Function FindSid ( 
	username As String
) As SecurityIdentifier
```

**VB Usage**<br />
``` VB Usage
Dim username As String
Dim returnValue As SecurityIdentifier

returnValue = UserAccountUtil.FindSid(username)
```

**C++**<br />
``` C++
public:
static SecurityIdentifier^ FindSid(
	String^ username
)
```

**F#**<br />
``` F#
static member FindSid : 
        username : string -> SecurityIdentifier 

```


#### Parameters
&nbsp;<dl><dt>username</dt><dd>Type: System.String<br />The user name.</dd></dl>

#### Return Value
Type: SecurityIdentifier<br />A SecurityIdentifier (SID) object.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim sid As SecurityIdentifier = UserAccounts.FindSid(username:="Administrator"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_UserAccountUtil">UserAccountUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />