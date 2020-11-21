# NativeMethods.UuidCreateSequential Method 
 

Creates a new UUID.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("RpcRt4.dll", SetLastError = true)]
public static Win32ErrorCode UuidCreateSequential(
	ref Guid refGuid
)
```

**VB**<br />
``` VB
<DllImportAttribute("RpcRt4.dll", SetLastError := true>]
Public Shared Function UuidCreateSequential ( 
	ByRef refGuid As Guid
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim refGuid As Guid
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.UuidCreateSequential(refGuid)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"RpcRt4.dll", SetLastError = true)]
static Win32ErrorCode UuidCreateSequential(
	Guid% refGuid
)
```

**F#**<br />
``` F#
[<DllImportAttribute("RpcRt4.dll", SetLastError = true)>]
static member UuidCreateSequential : 
        refGuid : Guid byref -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>refGuid</dt><dd>Type: System.Guid<br />Returns a pointer to the created UUID.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br /><a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>: The call succeeded. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">RPC_S_UUID_LOCAL_ONLY</a>: The UUID is guaranteed to be unique to this computer only. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">RPC_S_UUID_NO_ADDRESS</a>: Cannot get Ethernet or token-ring hardware address for this computer.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/rpcdce/nf-rpcdce-uuidcreatesequential" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/rpcdce/nf-rpcdce-uuidcreatesequential</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />