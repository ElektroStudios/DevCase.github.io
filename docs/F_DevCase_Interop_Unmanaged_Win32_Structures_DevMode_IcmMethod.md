# DevMode.IcmMethod Field
 

Specifies how ICM is handled. 

 For a non-ICM application, this member determines if ICM is enabled or disabled. 

 For ICM applications, the system examines this member to determine how to handle ICM support. 

 This member can be one of the following predefined values, or a driver-defined value greater than or equal to the value of `DMICMMETHOD_USER`.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int IcmMethod
```

**VB**<br />
``` VB
Public IcmMethod As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevMode
Dim value As Integer

value = instance.IcmMethod

instance.IcmMethod = value
```

**C++**<br />
``` C++
public:
int IcmMethod
```

**F#**<br />
``` F#
val mutable IcmMethod: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />