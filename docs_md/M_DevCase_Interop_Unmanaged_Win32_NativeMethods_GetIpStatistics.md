# NativeMethods.GetIpStatistics Method 
 

Retrieves the Internet Protocol (IP) statistics for the current computer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("IpHlpApi.dll", ExactSpelling = true)]
public static Win32ErrorCode GetIpStatistics(
	out IpStats refIpStats
)
```

**VB**<br />
``` VB
<DllImportAttribute("IpHlpApi.dll", ExactSpelling := true>]
Public Shared Function GetIpStatistics ( 
	<OutAttribute> ByRef refIpStats As IpStats
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim refIpStats As IpStats
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.GetIpStatistics(refIpStats)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"IpHlpApi.dll", ExactSpelling = true)]
static Win32ErrorCode GetIpStatistics(
	[OutAttribute] IpStats% refIpStats
)
```

**F#**<br />
``` F#
[<DllImportAttribute("IpHlpApi.dll", ExactSpelling = true)>]
static member GetIpStatistics : 
        refIpStats : IpStats byref -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>refIpStats</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IpStats">DevCase.Interop.Unmanaged.Win32.Structures.IpStats</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IpStats">IpStats</a> structure that receives the IP statistics for the local computer.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/iphlpapi/nf-iphlpapi-getipstatistics" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/iphlpapi/nf-iphlpapi-getipstatistics</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />