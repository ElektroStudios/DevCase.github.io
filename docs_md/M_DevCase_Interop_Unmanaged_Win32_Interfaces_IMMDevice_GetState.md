# IMMDevice.GetState Method 
 

Retrieves the current device state.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetState(
	ref EDeviceState refState
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetState ( 
	ByRef refState As EDeviceState
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMDevice
Dim refState As EDeviceState
Dim returnValue As HResult

returnValue = instance.GetState(refState)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetState(
	EDeviceState% refState
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetState : 
        refState : EDeviceState byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refState</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EDeviceState">DevCase.Interop.Unmanaged.Win32.Enums.EDeviceState</a><br />Pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EDeviceState">EDeviceState</a> variable into which the method writes the current state of the device.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice">IMMDevice Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />