# NativeMethods.SetIpStatistics Method 
 

Toggles IP forwarding on or off and sets the default time-to-live (TTL) value for the local computer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("IpHlpApi.dll", ExactSpelling = true)]
public static Win32ErrorCode SetIpStatistics(
	ref IpStats refIpStats
)
```

**VB**<br />
``` VB
<DllImportAttribute("IpHlpApi.dll", ExactSpelling := true>]
Public Shared Function SetIpStatistics ( 
	ByRef refIpStats As IpStats
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim refIpStats As IpStats
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.SetIpStatistics(refIpStats)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"IpHlpApi.dll", ExactSpelling = true)]
static Win32ErrorCode SetIpStatistics(
	IpStats% refIpStats
)
```

**F#**<br />
``` F#
[<DllImportAttribute("IpHlpApi.dll", ExactSpelling = true)>]
static member SetIpStatistics : 
        refIpStats : IpStats byref -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>refIpStats</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IpStats">DevCase.Interop.Unmanaged.Win32.Structures.IpStats</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IpStats">IpStats</a> structure. 

 The caller should set the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_Forwarding">Forwarding</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_DefaultTTL">DefaultTTL</a> members of this structure to the new values. 

 To keep one of the members at its current value, use MIB_USE_CURRENT_TTL or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_IpStatsForwarding">UseCurrentForwarding</a>.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/iphlpapi/nf-iphlpapi-setipstatistics" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/iphlpapi/nf-iphlpapi-setipstatistics</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />