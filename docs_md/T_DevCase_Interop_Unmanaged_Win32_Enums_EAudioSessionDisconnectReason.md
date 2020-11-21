# EAudioSessionDisconnectReason Enumeration
 

Defines constants that indicate the current state of an audio session. 

 The <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents_OnSessionDisconnected">OnSessionDisconnected(EAudioSessionDisconnectReason)</a> function use the constants defined in the EAudioSessionDisconnectReason enumeration.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum EAudioSessionDisconnectReason
```

**VB**<br />
``` VB
Public Enumeration EAudioSessionDisconnectReason
```

**VB Usage**<br />
``` VB Usage
Dim instance As EAudioSessionDisconnectReason
```

**C++**<br />
``` C++
public enum class EAudioSessionDisconnectReason
```

**F#**<br />
``` F#
type EAudioSessionDisconnectReason
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EAudioSessionDisconnectReason.DeviceRemoval">**DeviceRemoval**</td><td>0</td><td>The user removed the audio endpoint device.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EAudioSessionDisconnectReason.ServerShutdown">**ServerShutdown**</td><td>1</td><td>The Windows audio service has stopped.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EAudioSessionDisconnectReason.FormatChanged">**FormatChanged**</td><td>2</td><td>The stream format changed for the device that the audio session is connected to.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EAudioSessionDisconnectReason.SessionLogoff">**SessionLogoff**</td><td>3</td><td>The user logged off the Windows Terminal Services (WTS) session that the audio session was running in.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EAudioSessionDisconnectReason.SessionDisconnected">**SessionDisconnected**</td><td>4</td><td>The WTS session that the audio session was running in was disconnected.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EAudioSessionDisconnectReason.ExclusiveModeOverride">**ExclusiveModeOverride**</td><td>5</td><td>The (shared-mode) audio session was disconnected to make the audio endpoint device available for an exclusive-mode connection.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nf-audiopolicy-iaudiosessionevents-onsessiondisconnected" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nf-audiopolicy-iaudiosessionevents-onsessiondisconnected</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />