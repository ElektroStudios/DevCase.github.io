# IMMDeviceCollection.Item Method 
 

Retrieves a pointer to the specified item in the device collection.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
HResult Item(
	int deviceNumber,
	ref IMMDevice refDevice
)
```

**VB**<br />
``` VB
Function Item ( 
	deviceNumber As Integer,
	ByRef refDevice As IMMDevice
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMDeviceCollection
Dim deviceNumber As Integer
Dim refDevice As IMMDevice
Dim returnValue As HResult

returnValue = instance.Item(deviceNumber, 
	refDevice)
```

**C++**<br />
``` C++
HResult Item(
	int deviceNumber, 
	IMMDevice^% refDevice
)
```

**F#**<br />
``` F#
abstract Item : 
        deviceNumber : int * 
        refDevice : IMMDevice byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>deviceNumber</dt><dd>Type: System.Int32<br />The device number. If the collection contains n devices, the devices are numbered 0 to n– 1.</dd><dt>refDevice</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice">DevCase.Interop.Unmanaged.Win32.Interfaces.IMMDevice</a><br />Pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice">IMMDevice</a> variable into which the method writes the address of the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice">IMMDevice</a> interface of the specified item in the device collection. 

 Through this method, the caller obtains a counted reference to the interface. 

 The caller is responsible for releasing the interface, when it is no longer needed, by calling the interface's Release method. If the Item call fails, *refDevice* is a null reference (`Nothing` in Visual Basic).</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceCollection">IMMDeviceCollection Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />