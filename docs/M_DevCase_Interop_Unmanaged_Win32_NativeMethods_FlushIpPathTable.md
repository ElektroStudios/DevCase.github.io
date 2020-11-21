# NativeMethods.FlushIpPathTable Method 
 

Flushes the IP path table on the local computer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("IpHlpApi.dll", ExactSpelling = true)]
public static Win32ErrorCode FlushIpPathTable(
	AddressFamily family
)
```

**VB**<br />
``` VB
<DllImportAttribute("IpHlpApi.dll", ExactSpelling := true>]
Public Shared Function FlushIpPathTable ( 
	family As AddressFamily
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim family As AddressFamily
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.FlushIpPathTable(family)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"IpHlpApi.dll", ExactSpelling = true)]
static Win32ErrorCode FlushIpPathTable(
	AddressFamily family
)
```

**F#**<br />
``` F#
[<DllImportAttribute("IpHlpApi.dll", ExactSpelling = true)>]
static member FlushIpPathTable : 
        family : AddressFamily -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>family</dt><dd>Type: System.Net.Sockets.AddressFamily<br />The address family to flush. 

 The values currently supported are Unspecified, InterNetwork, and InterNetworkV6.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/netioapi/nf-netioapi-flushippathtable" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/netioapi/nf-netioapi-flushippathtable</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />