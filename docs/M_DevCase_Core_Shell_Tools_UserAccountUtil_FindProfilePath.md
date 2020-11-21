# UserAccountUtil.FindProfilePath Method (SecurityIdentifier)
 

Finds the profile directory path of the specified username account in the current machine context.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string FindProfilePath(
	SecurityIdentifier sid
)
```

**VB**<br />
``` VB
Public Shared Function FindProfilePath ( 
	sid As SecurityIdentifier
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sid As SecurityIdentifier
Dim returnValue As String

returnValue = UserAccountUtil.FindProfilePath(sid)
```

**C++**<br />
``` C++
public:
static String^ FindProfilePath(
	SecurityIdentifier^ sid
)
```

**F#**<br />
``` F#
static member FindProfilePath : 
        sid : SecurityIdentifier -> string 

```


#### Parameters
&nbsp;<dl><dt>sid</dt><dd>Type: System.Security.Principal.SecurityIdentifier<br />A SecurityIdentifier (SID) object.</dd></dl>

#### Return Value
Type: String<br />The profile directory path.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim profilePath As String = 
    UserAccounts.FindProfilePath(sid:=New SecurityIdentifier("S-1-5-21-1780771175-1208154119-2269826705-500"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_UserAccountUtil">UserAccountUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_UserAccountUtil_FindProfilePath">FindProfilePath Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />