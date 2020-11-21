# RegInfo(*T*).RegistryKey Property 
 

Gets a RegistryKey(RegistryKeyPermissionCheck, RegistryRights) instance of the current RootKey\SubKey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public RegistryKey this[
	RegistryKeyPermissionCheck registryKeyPermissionCheck = 0,
	RegistryRights registryOptions = 4
] { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property RegistryKey ( 
	Optional registryKeyPermissionCheck As RegistryKeyPermissionCheck = 0,
	Optional registryOptions As RegistryRights = 4
) As RegistryKey
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As RegInfo
Dim registryKeyPermissionCheck As RegistryKeyPermissionCheck
Dim registryOptions As RegistryRights
Dim value As RegistryKey

value = instance.RegistryKey(registryKeyPermissionCheck, 
	registryOptions)

```

**C++**<br />
``` C++
public:
property RegistryKey^ RegistryKey[RegistryKeyPermissionCheck registryKeyPermissionCheck = 0, RegistryRights registryOptions = 4] {
	RegistryKey^ get (RegistryKeyPermissionCheck registryKeyPermissionCheck = 0, RegistryRights registryOptions = 4);
}
```

**F#**<br />
``` F#
member RegistryKey : RegistryKey with get

```


#### Parameters
&nbsp;<dl><dt>registryKeyPermissionCheck (Optional)</dt><dd>Type: Microsoft.Win32.RegistryKeyPermissionCheck<br /></dd><dt>registryOptions (Optional)</dt><dd>Type: System.Security.AccessControl.RegistryRights<br /></dd></dl>

#### Property Value
Type: RegistryKey<br />A RegistryKey(RegistryKeyPermissionCheck, RegistryRights) instance of the current RootKey\SubKey.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_RegInfo_1">RegInfo(T) Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />