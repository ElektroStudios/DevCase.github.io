# IMMDeviceCollection.GetCount Method 
 

retrieves a count of the devices in the device collection.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
HResult GetCount(
	ref int refNumDevices
)
```

**VB**<br />
``` VB
Function GetCount ( 
	ByRef refNumDevices As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMDeviceCollection
Dim refNumDevices As Integer
Dim returnValue As HResult

returnValue = instance.GetCount(refNumDevices)
```

**C++**<br />
``` C++
HResult GetCount(
	int% refNumDevices
)
```

**F#**<br />
``` F#
abstract GetCount : 
        refNumDevices : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refNumDevices</dt><dd>Type: System.Int32<br />Pointer to a Int32 variable into which the method writes the number of devices in the device collection.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceCollection">IMMDeviceCollection Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />