# IconInfo.Mask Field
 

The icon bitmask bitmap. 

 If this structure defines a black and white icon, this bitmask is formatted so that the upper half is the icon `AND` bitmask and the lower half is the icon `XOR` bitmask. 

 Under this condition, the height should be an even multiple of two. 

 If this structure defines a color icon, this mask only defines the `AND` bitmask of the icon.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr Mask
```

**VB**<br />
``` VB
Public Mask As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As IconInfo
Dim value As IntPtr

value = instance.Mask

instance.Mask = value
```

**C++**<br />
``` C++
public:
IntPtr Mask
```

**F#**<br />
``` F#
val mutable Mask: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IconInfo">IconInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />