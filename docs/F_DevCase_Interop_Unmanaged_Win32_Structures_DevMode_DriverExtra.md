# DevMode.DriverExtra Field
 

Contains the number of bytes of private driver-data that follow this structure. 

 If a device driver does not use device-specific information, set this member to zero.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public short DriverExtra
```

**VB**<br />
``` VB
Public DriverExtra As Short
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevMode
Dim value As Short

value = instance.DriverExtra

instance.DriverExtra = value
```

**C++**<br />
``` C++
public:
short DriverExtra
```

**F#**<br />
``` F#
val mutable DriverExtra: int16
```


#### Field Value
Type: Int16

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />