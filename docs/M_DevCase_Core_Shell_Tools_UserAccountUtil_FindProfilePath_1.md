# UserAccountUtil.FindProfilePath Method (String)
 

Finds the profile directory path of the specified username account in the current machine context.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string FindProfilePath(
	string userName
)
```

**VB**<br />
``` VB
Public Shared Function FindProfilePath ( 
	userName As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim userName As String
Dim returnValue As String

returnValue = UserAccountUtil.FindProfilePath(userName)
```

**C++**<br />
``` C++
public:
static String^ FindProfilePath(
	String^ userName
)
```

**F#**<br />
``` F#
static member FindProfilePath : 
        userName : string -> string 

```


#### Parameters
&nbsp;<dl><dt>userName</dt><dd>Type: System.String<br />\[Missing <param name="userName"/> documentation for "M:DevCase.Core.Shell.Tools.UserAccountUtil.FindProfilePath(System.String)"\]</dd></dl>

#### Return Value
Type: String<br />The profile directory path.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim profilePath As String = UserAccounts.FindProfilePath(username:="Administrator"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_UserAccountUtil">UserAccountUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_UserAccountUtil_FindProfilePath">FindProfilePath Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />