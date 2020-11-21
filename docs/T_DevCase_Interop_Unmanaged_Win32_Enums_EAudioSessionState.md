# EAudioSessionState Enumeration
 

Defines constants that indicate the current state of an audio session. 

 The <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl_GetState">GetState(EAudioSessionState)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents_OnStateChanged">OnStateChanged(EAudioSessionState)</a> functions use the constants defined in the EAudioSessionState enumeration.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum EAudioSessionState
```

**VB**<br />
``` VB
Public Enumeration EAudioSessionState
```

**VB Usage**<br />
``` VB Usage
Dim instance As EAudioSessionState
```

**C++**<br />
``` C++
public enum class EAudioSessionState
```

**F#**<br />
``` F#
type EAudioSessionState
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EAudioSessionState.AudioSessionStateInactive">**AudioSessionStateInactive**</td><td>0</td><td>The audio session is inactive. (It contains at least one stream, but none of the streams in the session is currently running.)</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EAudioSessionState.AudioSessionStateActive">**AudioSessionStateActive**</td><td>1</td><td>The audio session is active. (At least one of the streams in the session is running.)</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EAudioSessionState.AudioSessionStateExpired">**AudioSessionStateExpired**</td><td>2</td><td>The audio session has expired. (It contains no streams.)</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/audiosessiontypes/ne-audiosessiontypes-_audiosessionstate" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/audiosessiontypes/ne-audiosessiontypes-_audiosessionstate</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />