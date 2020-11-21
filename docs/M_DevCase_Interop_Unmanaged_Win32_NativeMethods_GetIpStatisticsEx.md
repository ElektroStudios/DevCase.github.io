# NativeMethods.GetIpStatisticsEx Method 
 

Retrieves the Internet Protocol (IP) statistics for the current computer. 

 The GetIpStatisticsEx(IpStats, AddressFamily) function differs from the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetIpStatistics">GetIpStatistics(IpStats)</a> function in that GetIpStatisticsEx(IpStats, AddressFamily) also supports the Internet Protocol version 6 (IPv6) protocol family.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("IpHlpApi.dll", ExactSpelling = true)]
public static Win32ErrorCode GetIpStatisticsEx(
	out IpStats refIpStats,
	AddressFamily family
)
```

**VB**<br />
``` VB
<DllImportAttribute("IpHlpApi.dll", ExactSpelling := true>]
Public Shared Function GetIpStatisticsEx ( 
	<OutAttribute> ByRef refIpStats As IpStats,
	family As AddressFamily
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim refIpStats As IpStats
Dim family As AddressFamily
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.GetIpStatisticsEx(refIpStats, 
	family)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"IpHlpApi.dll", ExactSpelling = true)]
static Win32ErrorCode GetIpStatisticsEx(
	[OutAttribute] IpStats% refIpStats, 
	AddressFamily family
)
```

**F#**<br />
``` F#
[<DllImportAttribute("IpHlpApi.dll", ExactSpelling = true)>]
static member GetIpStatisticsEx : 
        refIpStats : IpStats byref * 
        family : AddressFamily -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>refIpStats</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IpStats">DevCase.Interop.Unmanaged.Win32.Structures.IpStats</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IpStats">IpStats</a> structure that receives the IP statistics for the local computer.</dd><dt>family</dt><dd>Type: System.Net.Sockets.AddressFamily<br />The protocol family for which to retrieve statistics. 

 The values currently supported are InterNetwork, and InterNetworkV6.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/iphlpapi/nf-iphlpapi-getipstatisticsex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/iphlpapi/nf-iphlpapi-getipstatisticsex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />