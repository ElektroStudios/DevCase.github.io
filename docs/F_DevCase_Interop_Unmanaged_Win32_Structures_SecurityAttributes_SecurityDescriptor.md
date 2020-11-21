# SecurityAttributes.SecurityDescriptor Field
 

A pointer to a `SECURITY_DESCRIPTOR` structure that controls access to the object. 

 If the value of this member is Zero, the object is assigned the default security descriptor associated with the access token of the calling process. 

 This is not the same as granting access to everyone by assigning a NULL discretionary access control list (DACL). 

 By default, the default DACL in the access token of a process allows access only to the user represented by the access token.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr SecurityDescriptor
```

**VB**<br />
``` VB
Public SecurityDescriptor As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As SecurityAttributes
Dim value As IntPtr

value = instance.SecurityDescriptor

instance.SecurityDescriptor = value
```

**C++**<br />
``` C++
public:
IntPtr SecurityDescriptor
```

**F#**<br />
``` F#
val mutable SecurityDescriptor: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">SecurityAttributes Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />