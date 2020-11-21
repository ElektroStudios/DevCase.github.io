# IpStats.DefaultTTL Field
 

The default initial time-to-live (TTL) for datagrams originating on a particular computer. 

 This member can be set to MIB_USE_CURRENT_TTL to use the current deafult TTL value when setting the forwarding and time-to-live (TTL) options using the SetIpStatistics and SetIpStatisticsEx functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public uint DefaultTTL
```

**VB**<br />
``` VB
Public DefaultTTL As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim instance As IpStats
Dim value As UInteger

value = instance.DefaultTTL

instance.DefaultTTL = value
```

**C++**<br />
``` C++
public:
unsigned int DefaultTTL
```

**F#**<br />
``` F#
val mutable DefaultTTL: uint32
```


#### Field Value
Type: UInt32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IpStats">IpStats Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />