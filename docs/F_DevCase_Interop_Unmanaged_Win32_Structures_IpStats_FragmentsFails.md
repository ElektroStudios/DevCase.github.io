# IpStats.FragmentsFails Field
 

The number of datagrams that have not been fragmented because the IP header specifies no fragmentation. These datagrams are discarded.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public uint FragmentsFails
```

**VB**<br />
``` VB
Public FragmentsFails As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim instance As IpStats
Dim value As UInteger

value = instance.FragmentsFails

instance.FragmentsFails = value
```

**C++**<br />
``` C++
public:
unsigned int FragmentsFails
```

**F#**<br />
``` F#
val mutable FragmentsFails: uint32
```


#### Field Value
Type: UInt32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IpStats">IpStats Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />