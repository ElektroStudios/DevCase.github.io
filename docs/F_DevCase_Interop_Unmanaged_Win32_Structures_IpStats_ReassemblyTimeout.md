# IpStats.ReassemblyTimeout Field
 

The amount of time allowed for all pieces of a fragmented datagram to arrive. 

 If all pieces do not arrive within this time, the datagram is discarded.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public uint ReassemblyTimeout
```

**VB**<br />
``` VB
Public ReassemblyTimeout As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim instance As IpStats
Dim value As UInteger

value = instance.ReassemblyTimeout

instance.ReassemblyTimeout = value
```

**C++**<br />
``` C++
public:
unsigned int ReassemblyTimeout
```

**F#**<br />
``` F#
val mutable ReassemblyTimeout: uint32
```


#### Field Value
Type: UInt32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IpStats">IpStats Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />