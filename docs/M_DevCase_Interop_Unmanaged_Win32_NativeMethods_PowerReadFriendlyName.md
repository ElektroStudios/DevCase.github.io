# NativeMethods.PowerReadFriendlyName Method 
 

Retrieves the friendly name for the specified power setting, subgroup, or scheme. 

 If the *schemeGuid* parameter is not a null reference (`Nothing` in Visual Basic) but both the *subGroupOfPowerSettingsGuid* and *powerSettingGuid* parameters are Zero, the friendly name of the power scheme will be returned. 

 If the *schemeGuid* is not a null reference (`Nothing` in Visual Basic), and *subGroupOfPowerSettingsGuid* parameter is not Zero, and the *powerSettingGuid* parameter is Zero, the friendly name of the subgroup will be returned. 

 If the *schemeGuid* is not a null reference (`Nothing` in Visual Basic), and *subGroupOfPowerSettingsGuid* and *powerSettingGuid* parameters are not Zero, the friendly name of the power setting will be returned.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("PowrProf.dll")]
public static Win32ErrorCode PowerReadFriendlyName(
	IntPtr rootPowerKey,
	Guid schemeGuid,
	IntPtr subGroupOfPowerSettingsGuid,
	IntPtr powerSettingGuid,
	IntPtr buffer,
	ref uint refBufferSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("PowrProf.dll">]
Public Shared Function PowerReadFriendlyName ( 
	rootPowerKey As IntPtr,
	schemeGuid As Guid,
	subGroupOfPowerSettingsGuid As IntPtr,
	powerSettingGuid As IntPtr,
	buffer As IntPtr,
	ByRef refBufferSize As UInteger
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim rootPowerKey As IntPtr
Dim schemeGuid As Guid
Dim subGroupOfPowerSettingsGuid As IntPtr
Dim powerSettingGuid As IntPtr
Dim buffer As IntPtr
Dim refBufferSize As UInteger
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.PowerReadFriendlyName(rootPowerKey, 
	schemeGuid, subGroupOfPowerSettingsGuid, 
	powerSettingGuid, buffer, refBufferSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"PowrProf.dll")]
static Win32ErrorCode PowerReadFriendlyName(
	IntPtr rootPowerKey, 
	Guid schemeGuid, 
	IntPtr subGroupOfPowerSettingsGuid, 
	IntPtr powerSettingGuid, 
	IntPtr buffer, 
	unsigned int% refBufferSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("PowrProf.dll")>]
static member PowerReadFriendlyName : 
        rootPowerKey : IntPtr * 
        schemeGuid : Guid * 
        subGroupOfPowerSettingsGuid : IntPtr * 
        powerSettingGuid : IntPtr * 
        buffer : IntPtr * 
        refBufferSize : uint32 byref -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>rootPowerKey</dt><dd>Type: System.IntPtr<br />Reserved for future use, this must be set to Zero.</dd><dt>schemeGuid</dt><dd>Type: System.Guid<br />The Guid referring to the power scheme.</dd><dt>subGroupOfPowerSettingsGuid</dt><dd>Type: System.IntPtr<br />The subgroup of power settings. 

 If this parameter is a null reference (`Nothing` in Visual Basic), an enumeration of settings under the `PolicyGuid` key is returned.</dd><dt>powerSettingGuid</dt><dd>Type: System.IntPtr<br /></dd><dt>buffer</dt><dd>Type: System.IntPtr<br />A pointer to a buffer that receives the friendly name. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the *refBufferSize* parameter receives the required buffer size. 

 The strings returned are all wide (Unicode) strings.</dd><dt>refBufferSize</dt><dd>Type: System.UInt32<br />A pointer to a variable that contains the size of the buffer pointed to by the Buffer parameter.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a> (zero) if the call was successful, and a nonzero value if the call failed. 

 If the buffer size specified by the *refBufferSize* parameter is too small, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_MORE_DATA</a> will be returned and the DWORD pointed to by the *refBufferSize* parameter will be filled in with the required buffer size.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa372740%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa372740%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />