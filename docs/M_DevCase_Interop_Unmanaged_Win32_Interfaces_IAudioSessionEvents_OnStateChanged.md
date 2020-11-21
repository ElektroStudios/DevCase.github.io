# IAudioSessionEvents.OnStateChanged Method 
 

Notifies the client that the stream-activity state of the session has changed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult OnStateChanged(
	EAudioSessionState state
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function OnStateChanged ( 
	state As EAudioSessionState
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionEvents
Dim state As EAudioSessionState
Dim returnValue As HResult

returnValue = instance.OnStateChanged(state)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult OnStateChanged(
	[InAttribute] EAudioSessionState state
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract OnStateChanged : 
        state : EAudioSessionState -> HResult 

```


#### Parameters
&nbsp;<dl><dt>state</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EAudioSessionState">DevCase.Interop.Unmanaged.Win32.Enums.EAudioSessionState</a><br />The new session state.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents">IAudioSessionEvents Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />