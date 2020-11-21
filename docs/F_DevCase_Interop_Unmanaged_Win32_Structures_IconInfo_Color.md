# IconInfo.Color Field
 

A handle to the icon color bitmap. 

 This member can be optional if this structure defines a black and white icon. 

 The `AND` bitmask of <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfo_Mask">Mask</a> member is applied with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TernaryRasterOperations">SrcAnd</a> flag to the destination; subsequently, the color bitmap is applied (using `XOR`) to the destination by using the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TernaryRasterOperations">SrcInvert</a> flag.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr Color
```

**VB**<br />
``` VB
Public Color As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As IconInfo
Dim value As IntPtr

value = instance.Color

instance.Color = value
```

**C++**<br />
``` C++
public:
IntPtr Color
```

**F#**<br />
``` F#
val mutable Color: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IconInfo">IconInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />