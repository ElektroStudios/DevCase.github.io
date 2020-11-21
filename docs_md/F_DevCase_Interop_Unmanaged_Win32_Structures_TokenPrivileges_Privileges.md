# TokenPrivileges.Privileges Field
 

Specifies an array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_LuidAndAttributes">LuidAndAttributes</a> structures. 

 Each structure contains the LUID and attributes of a privilege. 

 To get the name of the privilege associated with a LUID, call the `LookupPrivilegeName` function, passing the address of the LUID as the value of the `lpLuid` parameter.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public LuidAndAttributes[] Privileges
```

**VB**<br />
``` VB
Public Privileges As LuidAndAttributes()
```

**VB Usage**<br />
``` VB Usage
Dim instance As TokenPrivileges
Dim value As LuidAndAttributes()

value = instance.Privileges

instance.Privileges = value
```

**C++**<br />
``` C++
public:
array<LuidAndAttributes>^ Privileges
```

**F#**<br />
``` F#
val mutable Privileges: LuidAndAttributes[]
```


#### Field Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_LuidAndAttributes">LuidAndAttributes</a>[]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_TokenPrivileges">TokenPrivileges Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />