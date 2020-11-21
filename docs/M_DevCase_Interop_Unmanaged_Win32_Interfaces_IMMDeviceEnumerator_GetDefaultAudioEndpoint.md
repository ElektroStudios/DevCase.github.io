# IMMDeviceEnumerator.GetDefaultAudioEndpoint Method 
 

Retrieves the default audio endpoint for the specified data-flow direction and role.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetDefaultAudioEndpoint(
	EDataFlow dataFlow,
	ERole role,
	out IMMDevice refDevice
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetDefaultAudioEndpoint ( 
	dataFlow As EDataFlow,
	role As ERole,
	<OutAttribute> ByRef refDevice As IMMDevice
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMDeviceEnumerator
Dim dataFlow As EDataFlow
Dim role As ERole
Dim refDevice As IMMDevice
Dim returnValue As HResult

returnValue = instance.GetDefaultAudioEndpoint(dataFlow, 
	role, refDevice)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetDefaultAudioEndpoint(
	[InAttribute] EDataFlow dataFlow, 
	[InAttribute] ERole role, 
	[OutAttribute] IMMDevice^% refDevice
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetDefaultAudioEndpoint : 
        dataFlow : EDataFlow * 
        role : ERole * 
        refDevice : IMMDevice byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>dataFlow</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EDataFlow">DevCase.Interop.Unmanaged.Win32.Enums.EDataFlow</a><br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EDataFlow">EDataFlow</a> direction for the endpoint device.</dd><dt>role</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ERole">DevCase.Interop.Unmanaged.Win32.Enums.ERole</a><br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ERole">ERole</a> of the endpoint device.</dd><dt>refDevice</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice">DevCase.Interop.Unmanaged.Win32.Interfaces.IMMDevice</a><br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice">IMMDevice</a> interface of the default audio endpoint device.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator">IMMDeviceEnumerator Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />