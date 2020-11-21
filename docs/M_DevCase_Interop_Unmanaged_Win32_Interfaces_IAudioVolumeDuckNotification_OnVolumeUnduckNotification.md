# IAudioVolumeDuckNotification.OnVolumeUnduckNotification Method 
 

Sends a notification about a pending system unducking event.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult OnVolumeUnduckNotification(
	string sessionId
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function OnVolumeUnduckNotification ( 
	sessionId As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioVolumeDuckNotification
Dim sessionId As String
Dim returnValue As HResult

returnValue = instance.OnVolumeUnduckNotification(sessionId)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult OnVolumeUnduckNotification(
	[InAttribute] String^ sessionId
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract OnVolumeUnduckNotification : 
        sessionId : string -> HResult 

```


#### Parameters
&nbsp;<dl><dt>sessionId</dt><dd>Type: System.String<br />A string containing the session instance identifier of the terminating communications session that intiated the ducking. 

 To get the session instance identifier, call <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_GetSessionInstanceIdentifier">GetSessionInstanceIdentifier(String)</a>.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioVolumeDuckNotification">IAudioVolumeDuckNotification Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />