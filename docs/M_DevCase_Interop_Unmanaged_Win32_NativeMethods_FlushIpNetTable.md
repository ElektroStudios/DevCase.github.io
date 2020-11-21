# NativeMethods.FlushIpNetTable Method 
 

Deletes all ARP entries for the specified interface from the ARP table on the local computer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("IpHlpApi.dll", ExactSpelling = true)]
public static Win32ErrorCode FlushIpNetTable(
	uint interfaceIndex
)
```

**VB**<br />
``` VB
<DllImportAttribute("IpHlpApi.dll", ExactSpelling := true>]
Public Shared Function FlushIpNetTable ( 
	interfaceIndex As UInteger
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim interfaceIndex As UInteger
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.FlushIpNetTable(interfaceIndex)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"IpHlpApi.dll", ExactSpelling = true)]
static Win32ErrorCode FlushIpNetTable(
	unsigned int interfaceIndex
)
```

**F#**<br />
``` F#
[<DllImportAttribute("IpHlpApi.dll", ExactSpelling = true)>]
static member FlushIpNetTable : 
        interfaceIndex : uint32 -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>interfaceIndex</dt><dd>Type: System.UInt32<br />The index of the interface for which to delete all ARP entries.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/iphlpapi/nf-iphlpapi-flushipnettable" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/iphlpapi/nf-iphlpapi-flushipnettable</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />