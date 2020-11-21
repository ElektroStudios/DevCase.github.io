# BlendFunction.SourceConstantAlpha Field
 

Specifies an alpha transparency value to be used on the entire source bitmap. 

 The SourceConstantAlpha value is combined with any per-pixel alpha values in the source bitmap. 

 If you set SourceConstantAlpha to 0, it is assumed that your image is transparent. 

 Set the SourceConstantAlpha value to 255 (opaque) when you only want to use per-pixel alpha values.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public byte SourceConstantAlpha
```

**VB**<br />
``` VB
Public SourceConstantAlpha As Byte
```

**VB Usage**<br />
``` VB Usage
Dim instance As BlendFunction
Dim value As Byte

value = instance.SourceConstantAlpha

instance.SourceConstantAlpha = value
```

**C++**<br />
``` C++
public:
unsigned char SourceConstantAlpha
```

**F#**<br />
``` F#
val mutable SourceConstantAlpha: byte
```


#### Field Value
Type: Byte

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_BlendFunction">BlendFunction Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />