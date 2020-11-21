# PrivilegeSet.Control Field
 

Specifies a control flag related to the privileges. 

 The `PRIVILEGE_SET_ALL_NECESSARY` control flag is currently defined. 

 It indicates that all of the specified privileges must be held by the process requesting access. 

 If this flag is not set, the presence of any privileges in the user's access token grants the access.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public uint Control
```

**VB**<br />
``` VB
Public Control As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim instance As PrivilegeSet
Dim value As UInteger

value = instance.Control

instance.Control = value
```

**C++**<br />
``` C++
public:
unsigned int Control
```

**F#**<br />
``` F#
val mutable Control: uint32
```


#### Field Value
Type: UInt32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PrivilegeSet">PrivilegeSet Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />