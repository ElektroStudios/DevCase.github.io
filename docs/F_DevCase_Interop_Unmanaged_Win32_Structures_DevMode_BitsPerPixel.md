# DevMode.BitsPerPixel Field
 

Specifies the color resolution, in bits per pixel, of the display device (for example: 4 bits for 16 colors, 8 bits for 256 colors, or 16 bits for 65,536 colors). 

 Display drivers use this member, for example, in the `ChangeDisplaySettings` function. 

 Printer drivers do not use this member.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int BitsPerPixel
```

**VB**<br />
``` VB
Public BitsPerPixel As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevMode
Dim value As Integer

value = instance.BitsPerPixel

instance.BitsPerPixel = value
```

**C++**<br />
``` C++
public:
int BitsPerPixel
```

**F#**<br />
``` F#
val mutable BitsPerPixel: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />