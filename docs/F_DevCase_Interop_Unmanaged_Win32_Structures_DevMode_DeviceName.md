# DevMode.DeviceName Field
 

A zero-terminated character array that specifies the "friendly" name of the printer or display; for example, "`PCL/HP LaserJet`" in the case of PCL/HP LaserJet. This string is unique among device drivers. 

 Note that this name may be truncated to fit in the DeviceName array.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string DeviceName
```

**VB**<br />
``` VB
Public DeviceName As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevMode
Dim value As String

value = instance.DeviceName

instance.DeviceName = value
```

**C++**<br />
``` C++
public:
String^ DeviceName
```

**F#**<br />
``` F#
val mutable DeviceName: string
```


#### Field Value
Type: String

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />