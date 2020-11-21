# IMMDeviceEnumerator.EnumAudioEndpoints Method 
 

Generates a collection of audio endpoint devices that meet the specified criteria.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult EnumAudioEndpoints(
	EDataFlow dataFlow,
	EDeviceState stateMask,
	out IMMDeviceCollection refDevices
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function EnumAudioEndpoints ( 
	dataFlow As EDataFlow,
	stateMask As EDeviceState,
	<OutAttribute> ByRef refDevices As IMMDeviceCollection
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMDeviceEnumerator
Dim dataFlow As EDataFlow
Dim stateMask As EDeviceState
Dim refDevices As IMMDeviceCollection
Dim returnValue As HResult

returnValue = instance.EnumAudioEndpoints(dataFlow, 
	stateMask, refDevices)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult EnumAudioEndpoints(
	[InAttribute] EDataFlow dataFlow, 
	[InAttribute] EDeviceState stateMask, 
	[OutAttribute] IMMDeviceCollection^% refDevices
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract EnumAudioEndpoints : 
        dataFlow : EDataFlow * 
        stateMask : EDeviceState * 
        refDevices : IMMDeviceCollection byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>dataFlow</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EDataFlow">DevCase.Interop.Unmanaged.Win32.Enums.EDataFlow</a><br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EDataFlow">EDataFlow</a> direction for the endpoint devices in the collection.</dd><dt>stateMask</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EDeviceState">DevCase.Interop.Unmanaged.Win32.Enums.EDeviceState</a><br />One or more <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EDeviceState">EDeviceState</a> constants that indicate the state of the endpoints in the collection.</dd><dt>refDevices</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceCollection">DevCase.Interop.Unmanaged.Win32.Interfaces.IMMDeviceCollection</a><br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceCollection">IMMDeviceCollection</a> interface of the device-collection object.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator">IMMDeviceEnumerator Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />