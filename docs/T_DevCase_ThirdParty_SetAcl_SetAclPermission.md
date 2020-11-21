# SetAclPermission Enumeration
 

Specifies a SetACL registry permission.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SetAcl">DevCase.ThirdParty.SetAcl</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum SetAclPermission
```

**VB**<br />
``` VB
Public Enumeration SetAclPermission
```

**VB Usage**<br />
``` VB Usage
Dim instance As SetAclPermission
```

**C++**<br />
``` C++
public enum class SetAclPermission
```

**F#**<br />
``` F#
type SetAclPermission
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.ThirdParty.SetAcl.SetAclPermission.Create_Link">**Create_Link**</td><td>0</td><td>Create link.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.SetAcl.SetAclPermission.Create_Subkey">**Create_Subkey**</td><td>1</td><td>Create subkeys.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.SetAcl.SetAclPermission.Delete">**Delete**</td><td>2</td><td>Delete.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.SetAcl.SetAclPermission.Enum_Subkeys">**Enum_Subkeys**</td><td>3</td><td>Enumerate subkeys.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.SetAcl.SetAclPermission.Notify">**Notify**</td><td>4</td><td>Notify.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.SetAcl.SetAclPermission.Query_val">**Query_val**</td><td>5</td><td>Query value.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.SetAcl.SetAclPermission.Read_Access">**Read_Access**</td><td>6</td><td>Read control.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.SetAcl.SetAclPermission.Set_Val">**Set_Val**</td><td>7</td><td>Set value.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.SetAcl.SetAclPermission.Write_DACL">**Write_DACL**</td><td>8</td><td>Write permissions.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.SetAcl.SetAclPermission.Write_Owner">**Write_Owner**</td><td>9</td><td>Take ownership.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.SetAcl.SetAclPermission.Read">**Read**</td><td>10</td><td>Read. 

 (KEY_ENUMERATE_SUB_KEYS + KEY_EXECUTE + KEY_NOTIFY + KEY_QUERY_VALUE + KEY_READ + READ_CONTROL)</td></tr><tr><td /><td target="F:DevCase.ThirdParty.SetAcl.SetAclPermission.Full">**Full**</td><td>11</td><td>Full access. 

 (KEY_CREATE_LINK + KEY_CREATE_SUB_KEY + KEY_ENUMERATE_SUB_KEYS + KEY_EXECUTE + KEY_NOTIFY + KEY_QUERY_VALUE + KEY_READ + KEY_SET_VALUE + KEY_WRITE + READ_CONTROL + WRITE_OWNER + WRITE_DAC + DELETE)</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_SetAcl">DevCase.ThirdParty.SetAcl Namespace</a><br />