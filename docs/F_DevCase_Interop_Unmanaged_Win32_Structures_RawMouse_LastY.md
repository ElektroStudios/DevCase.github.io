# RawMouse.LastY Field
 

The motion in the Y direction. 

 This is signed relative motion or absolute motion, depending on the value of <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawMouse_Flags">Flags</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FieldOffsetAttribute(16)]
public int LastY
```

**VB**<br />
``` VB
<FieldOffsetAttribute(16)>
Public LastY As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As RawMouse
Dim value As Integer

value = instance.LastY

instance.LastY = value
```

**C++**<br />
``` C++
public:
[FieldOffsetAttribute(16)]
int LastY
```

**F#**<br />
``` F#
[<FieldOffsetAttribute(16)>]
val mutable LastY: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawMouse">RawMouse Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />