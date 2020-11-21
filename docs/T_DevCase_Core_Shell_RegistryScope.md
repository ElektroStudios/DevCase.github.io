# RegistryScope Enumeration
 

Specifies a registry scope (a root key).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum RegistryScope
```

**VB**<br />
``` VB
Public Enumeration RegistryScope
```

**VB Usage**<br />
``` VB Usage
Dim instance As RegistryScope
```

**C++**<br />
``` C++
public enum class RegistryScope
```

**F#**<br />
``` F#
type RegistryScope
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Shell.RegistryScope.Machine">**Machine**</td><td>0</td><td>This refers to the HKEY_LOCAL_MACHINE (or HKLM) registry root key. 

 Configuration changes made on the subkeys of this root key will affect all users.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.RegistryScope.CurrentUser">**CurrentUser**</td><td>1</td><td>This refers to the HKEY_CURRENT_USER (or HKCU) registry root key. 

 Configuration changes made on the subkeys of this root key will affect only the current user.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />