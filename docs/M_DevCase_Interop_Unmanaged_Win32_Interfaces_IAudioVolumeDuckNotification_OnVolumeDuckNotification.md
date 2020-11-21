# IAudioVolumeDuckNotification.OnVolumeDuckNotification Method 
 

Sends a notification about a pending system ducking event.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult OnVolumeDuckNotification(
	string sessionId,
	uint countCommunicationSessions
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function OnVolumeDuckNotification ( 
	sessionId As String,
	countCommunicationSessions As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioVolumeDuckNotification
Dim sessionId As String
Dim countCommunicationSessions As UInteger
Dim returnValue As HResult

returnValue = instance.OnVolumeDuckNotification(sessionId, 
	countCommunicationSessions)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult OnVolumeDuckNotification(
	[InAttribute] String^ sessionId, 
	[InAttribute] unsigned int countCommunicationSessions
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract OnVolumeDuckNotification : 
        sessionId : string * 
        countCommunicationSessions : uint32 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>sessionId</dt><dd>Type: System.String<br />A string containing the session instance identifier of the communications session that raises the the auto-ducking event. 

 To get the session instance identifier, call <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_GetSessionInstanceIdentifier">GetSessionInstanceIdentifier(String)</a>.</dd><dt>countCommunicationSessions</dt><dd>Type: System.UInt32<br /></dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioVolumeDuckNotification">IAudioVolumeDuckNotification Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />