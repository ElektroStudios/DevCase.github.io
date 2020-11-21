# IMMNotificationClient.OnPropertyValueChanged Method 
 

Indicates that the value of a property belonging to an audio endpoint device has changed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult OnPropertyValueChanged(
	string deviceId,
	PropertyKey propertyKey
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function OnPropertyValueChanged ( 
	deviceId As String,
	propertyKey As PropertyKey
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMNotificationClient
Dim deviceId As String
Dim propertyKey As PropertyKey
Dim returnValue As HResult

returnValue = instance.OnPropertyValueChanged(deviceId, 
	propertyKey)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult OnPropertyValueChanged(
	String^ deviceId, 
	PropertyKey propertyKey
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract OnPropertyValueChanged : 
        deviceId : string * 
        propertyKey : PropertyKey -> HResult 

```


#### Parameters
&nbsp;<dl><dt>deviceId</dt><dd>Type: System.String<br />The endpoint ID string that identifies the audio endpoint device.</dd><dt>propertyKey</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PropertyKey">DevCase.Interop.Unmanaged.Win32.Structures.PropertyKey</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PropertyKey">PropertyKey</a> that specifies the type of property.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IMMNotificationClient.OnPropertyValueChanged(System.String,DevCase.Interop.Unmanaged.Win32.Structures.PropertyKey)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMNotificationClient">IMMNotificationClient Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />