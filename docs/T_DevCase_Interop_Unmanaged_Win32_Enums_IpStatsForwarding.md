# IpStatsForwarding Enumeration
 

Specifies whether IP forwarding is enabled or disabled for a protocol (IPv4 or IPv6).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum IpStatsForwarding
```

**VB**<br />
``` VB
Public Enumeration IpStatsForwarding
```

**VB Usage**<br />
``` VB Usage
Dim instance As IpStatsForwarding
```

**C++**<br />
``` C++
public enum class IpStatsForwarding
```

**F#**<br />
``` F#
type IpStatsForwarding
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IpStatsForwarding.IpForwarding">**IpForwarding**</td><td>1</td><td>IP forwarding is enabled.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IpStatsForwarding.IpNotForwarding">**IpNotForwarding**</td><td>2</td><td>IP forwarding is not enabled.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IpStatsForwarding.UseCurrentForwarding">**UseCurrentForwarding**</td><td>-1</td><td>Use the current IP forwarding setting. 

 This value is only applicable when setting the forwarding and time-to-live (TTL) options using the SetIpStatistics and SetIpStatisticsEx functions.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-rrasm/7360b8dd-dd22-436c-ac87-1bd5dfe21bb6" target="_blank">https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-rrasm/7360b8dd-dd22-436c-ac87-1bd5dfe21bb6</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />