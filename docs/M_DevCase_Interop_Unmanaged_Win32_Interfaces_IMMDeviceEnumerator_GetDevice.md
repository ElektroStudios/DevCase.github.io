# IMMDeviceEnumerator.GetDevice Method 
 

Retrieves an endpoint device that is specified by an endpoint device-identification string.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetDevice(
	string endpointId,
	out IMMDevice refDevice
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetDevice ( 
	endpointId As String,
	<OutAttribute> ByRef refDevice As IMMDevice
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMDeviceEnumerator
Dim endpointId As String
Dim refDevice As IMMDevice
Dim returnValue As HResult

returnValue = instance.GetDevice(endpointId, 
	refDevice)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetDevice(
	[InAttribute] String^ endpointId, 
	[OutAttribute] IMMDevice^% refDevice
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetDevice : 
        endpointId : string * 
        refDevice : IMMDevice byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>endpointId</dt><dd>Type: System.String<br />The endpoint ID.</dd><dt>refDevice</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice">DevCase.Interop.Unmanaged.Win32.Interfaces.IMMDevice</a><br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice">IMMDevice</a> interface for the specified device.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator">IMMDeviceEnumerator Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />