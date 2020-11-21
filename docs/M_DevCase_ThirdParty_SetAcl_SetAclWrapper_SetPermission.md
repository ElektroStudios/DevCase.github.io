# SetAclWrapper.SetPermission Method 
 

Takes ownership of a registry key.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SetAcl">DevCase.ThirdParty.SetAcl</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int SetPermission(
	string regKey,
	bool recursive,
	SetAclPermission permission,
	string userName = ""
)
```

**VB**<br />
``` VB
Public Function SetPermission ( 
	regKey As String,
	recursive As Boolean,
	permission As SetAclPermission,
	Optional userName As String = ""
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As SetAclWrapper
Dim regKey As String
Dim recursive As Boolean
Dim permission As SetAclPermission
Dim userName As String
Dim returnValue As Integer

returnValue = instance.SetPermission(regKey, 
	recursive, permission, userName)
```

**C++**<br />
``` C++
public:
int SetPermission(
	String^ regKey, 
	bool recursive, 
	SetAclPermission permission, 
	String^ userName = L""
)
```

**F#**<br />
``` F#
member SetPermission : 
        regKey : string * 
        recursive : bool * 
        permission : SetAclPermission * 
        ?userName : string 
(* Defaults:
        let _userName = defaultArg userName ""
*)
-> int 

```


#### Parameters
&nbsp;<dl><dt>regKey</dt><dd>Type: System.String<br />The registry key.</dd><dt>recursive</dt><dd>Type: System.Boolean<br />A value indicating whether to set ownership on all sub-keys.</dd><dt>permission</dt><dd>Type: <a href="T_DevCase_ThirdParty_SetAcl_SetAclPermission">DevCase.ThirdParty.SetAcl.SetAclPermission</a><br />The permission to set.</dd><dt>userName (Optional)</dt><dd>Type: System.String<br />The account username.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SetAcl_SetAclWrapper">SetAclWrapper Class</a><br /><a href="N_DevCase_ThirdParty_SetAcl">DevCase.ThirdParty.SetAcl Namespace</a><br />