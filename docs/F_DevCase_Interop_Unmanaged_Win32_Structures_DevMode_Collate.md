# DevMode.Collate Field
 

Specifies whether collation should be used when printing multiple copies. 

 This member is ignored unless the printer driver indicates support for collation by setting the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_Fields">Fields</a> member to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DeviceModeFields">Collate</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public short Collate
```

**VB**<br />
``` VB
Public Collate As Short
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevMode
Dim value As Short

value = instance.Collate

instance.Collate = value
```

**C++**<br />
``` C++
public:
short Collate
```

**F#**<br />
``` F#
val mutable Collate: int16
```


#### Field Value
Type: Int16

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />