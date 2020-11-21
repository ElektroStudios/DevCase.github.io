# NativeMethods.FlushIpNetTable2 Method 
 

Flushes the IP neighbor table on the local computer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("IpHlpApi.dll", ExactSpelling = true)]
public static Win32ErrorCode FlushIpNetTable2(
	AddressFamily family,
	uint interfaceIndex
)
```

**VB**<br />
``` VB
<DllImportAttribute("IpHlpApi.dll", ExactSpelling := true>]
Public Shared Function FlushIpNetTable2 ( 
	family As AddressFamily,
	interfaceIndex As UInteger
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim family As AddressFamily
Dim interfaceIndex As UInteger
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.FlushIpNetTable2(family, 
	interfaceIndex)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"IpHlpApi.dll", ExactSpelling = true)]
static Win32ErrorCode FlushIpNetTable2(
	AddressFamily family, 
	unsigned int interfaceIndex
)
```

**F#**<br />
``` F#
[<DllImportAttribute("IpHlpApi.dll", ExactSpelling = true)>]
static member FlushIpNetTable2 : 
        family : AddressFamily * 
        interfaceIndex : uint32 -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>family</dt><dd>Type: System.Net.Sockets.AddressFamily<br />The address family to flush. 

 The values currently supported are Unspecified, InterNetwork, and InterNetworkV6.</dd><dt>interfaceIndex</dt><dd>Type: System.UInt32<br />The interface index. 

 If the index is specified, flush the neighbor IP address entries on a specific interface, otherwise flush the neighbor IP address entries on all the interfaces. 

 To ignore the interface, set this parameter to zero.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/netioapi/nf-netioapi-flushipnettable2" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/netioapi/nf-netioapi-flushipnettable2</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />