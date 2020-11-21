# ObjectAttributes.SecurityDescriptor Field
 

Specifies a security descriptor for the object when the object is created. 

 If this member is Zero, the object will receive default security settings.

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
Dim instance As ObjectAttributes
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
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes">ObjectAttributes Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />