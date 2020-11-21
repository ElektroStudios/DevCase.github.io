# UserAccountUtil.FindUsername Method 
 

Finds the username of the specified security identifier (SID) in the current machine context.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string FindUsername(
	SecurityIdentifier sid
)
```

**VB**<br />
``` VB
Public Shared Function FindUsername ( 
	sid As SecurityIdentifier
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sid As SecurityIdentifier
Dim returnValue As String

returnValue = UserAccountUtil.FindUsername(sid)
```

**C++**<br />
``` C++
public:
static String^ FindUsername(
	SecurityIdentifier^ sid
)
```

**F#**<br />
``` F#
static member FindUsername : 
        sid : SecurityIdentifier -> string 

```


#### Parameters
&nbsp;<dl><dt>sid</dt><dd>Type: System.Security.Principal.SecurityIdentifier<br />A SecurityIdentifier (SID) object.</dd></dl>

#### Return Value
Type: String<br />The username.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim username As String = UserAccounts.FindUsername(sid:=New SecurityIdentifier("S-1-5-21-1780771175-1208154119-2269826705-500"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_UserAccountUtil">UserAccountUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />