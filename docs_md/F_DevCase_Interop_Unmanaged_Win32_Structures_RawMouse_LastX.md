# RawMouse.LastX Field
 

The motion in the X direction. 

 This is signed relative motion or absolute motion, depending on the value of <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawMouse_Flags">Flags</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FieldOffsetAttribute(12)]
public int LastX
```

**VB**<br />
``` VB
<FieldOffsetAttribute(12)>
Public LastX As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As RawMouse
Dim value As Integer

value = instance.LastX

instance.LastX = value
```

**C++**<br />
``` C++
public:
[FieldOffsetAttribute(12)]
int LastX
```

**F#**<br />
``` F#
[<FieldOffsetAttribute(12)>]
val mutable LastX: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawMouse">RawMouse Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />