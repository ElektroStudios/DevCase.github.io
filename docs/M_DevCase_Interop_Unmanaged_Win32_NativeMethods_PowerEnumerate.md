# NativeMethods.PowerEnumerate Method 
 

Enumerates the specified elements in a power scheme. 

 This function is normally called in a loop incrementing the Index parameter to retrieve subkeys until they've all been enumerated.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("PowrProf.dll")]
public static Win32ErrorCode PowerEnumerate(
	IntPtr rootPowerKey,
	IntPtr schemeGuid,
	IntPtr subGroupOfPowerSettingsGuid,
	PowerPlanAccess acessFlags,
	uint index,
	ref Guid refBuffer,
	ref uint refBufferSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("PowrProf.dll">]
Public Shared Function PowerEnumerate ( 
	rootPowerKey As IntPtr,
	schemeGuid As IntPtr,
	subGroupOfPowerSettingsGuid As IntPtr,
	acessFlags As PowerPlanAccess,
	index As UInteger,
	ByRef refBuffer As Guid,
	ByRef refBufferSize As UInteger
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim rootPowerKey As IntPtr
Dim schemeGuid As IntPtr
Dim subGroupOfPowerSettingsGuid As IntPtr
Dim acessFlags As PowerPlanAccess
Dim index As UInteger
Dim refBuffer As Guid
Dim refBufferSize As UInteger
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.PowerEnumerate(rootPowerKey, 
	schemeGuid, subGroupOfPowerSettingsGuid, 
	acessFlags, index, refBuffer, refBufferSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"PowrProf.dll")]
static Win32ErrorCode PowerEnumerate(
	IntPtr rootPowerKey, 
	IntPtr schemeGuid, 
	IntPtr subGroupOfPowerSettingsGuid, 
	PowerPlanAccess acessFlags, 
	unsigned int index, 
	Guid% refBuffer, 
	unsigned int% refBufferSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("PowrProf.dll")>]
static member PowerEnumerate : 
        rootPowerKey : IntPtr * 
        schemeGuid : IntPtr * 
        subGroupOfPowerSettingsGuid : IntPtr * 
        acessFlags : PowerPlanAccess * 
        index : uint32 * 
        refBuffer : Guid byref * 
        refBufferSize : uint32 byref -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>rootPowerKey</dt><dd>Type: System.IntPtr<br />Reserved for future use, this must be set to Zero.</dd><dt>schemeGuid</dt><dd>Type: System.IntPtr<br />The Guid referring to the power scheme.</dd><dt>subGroupOfPowerSettingsGuid</dt><dd>Type: System.IntPtr<br />The subgroup of power settings. 

 If this parameter is a null reference (`Nothing` in Visual Basic), an enumeration of settings under the `PolicyGuid` key is returned.</dd><dt>acessFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PowerPlanAccess">DevCase.Interop.Unmanaged.Win32.Enums.PowerPlanAccess</a><br />A set of flags that specifies what will be enumerated.</dd><dt>index</dt><dd>Type: System.UInt32<br />The zero-based index Of the scheme, subgroup, Or setting that Is being enumerated.</dd><dt>refBuffer</dt><dd>Type: System.Guid<br />A pointer To a variable To receive the elements. 

 If this parameter Is a null reference (`Nothing` in Visual Basic), the Function retrieves the size Of the buffer required.</dd><dt>refBufferSize</dt><dd>Type: System.UInt32<br />A pointer to a variable that contains the size of the buffer pointed to by the Buffer parameter.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a> (zero) if the call was successful, and a nonzero value if the call failed. 

 If the buffer size specified by the *refBufferSize* parameter is too small, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_MORE_DATA</a> will be returned and the DWORD pointed to by the *refBufferSize* parameter will be filled in with the required buffer size.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa372730%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa372730%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />