# DevMode.Fields Field
 

Specifies whether certain members of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode</a> structure have been initialized. 

 If a member is initialized, its corresponding bit is set, otherwise the bit is clear. 

 A driver supports only those <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode</a> members that are appropriate for the printer or display technology.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public DeviceModeFields Fields
```

**VB**<br />
``` VB
Public Fields As DeviceModeFields
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevMode
Dim value As DeviceModeFields

value = instance.Fields

instance.Fields = value
```

**C++**<br />
``` C++
public:
DeviceModeFields Fields
```

**F#**<br />
``` F#
val mutable Fields: DeviceModeFields
```


#### Field Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DeviceModeFields">DeviceModeFields</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />