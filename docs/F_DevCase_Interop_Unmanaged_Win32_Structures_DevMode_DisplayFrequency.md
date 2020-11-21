# DevMode.DisplayFrequency Field
 

Only for Display drivers, specifies the frequency, in hertz (cycles per second), of the display device in a particular mode. 

 This value is also known as the display device's vertical refresh rate. 

 It is used, for example, in the `ChangeDisplaySettings` function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int DisplayFrequency
```

**VB**<br />
``` VB
Public DisplayFrequency As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevMode
Dim value As Integer

value = instance.DisplayFrequency

instance.DisplayFrequency = value
```

**C++**<br />
``` C++
public:
int DisplayFrequency
```

**F#**<br />
``` F#
val mutable DisplayFrequency: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />