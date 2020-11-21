# IAudioSessionControl2 Interface
 

Enables a client to configure the control parameters for an audio session and to monitor events in the session. 

 The IAudioClient.Initialize method initializes a stream object and assigns the stream to an audio session.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("BFB7FF88-7239-4FC9-8FA2-07C950BE9C6D")]
public interface IAudioSessionControl2
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("BFB7FF88-7239-4FC9-8FA2-07C950BE9C6D")>
Public Interface IAudioSessionControl2
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionControl2
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"BFB7FF88-7239-4FC9-8FA2-07C950BE9C6D")]
public interface class IAudioSessionControl2
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("BFB7FF88-7239-4FC9-8FA2-07C950BE9C6D")>]
type IAudioSessionControl2 =  interface end
```

The IAudioSessionControl2 type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_GetDisplayName">GetDisplayName</a></td><td>
Retrieves the display name for the audio session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_GetGroupingParam">GetGroupingParam</a></td><td>
Retrieves the grouping parameter of the audio session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_GetIconPath">GetIconPath</a></td><td>
Retrieves the path for the display icon for the audio session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_GetProcessId">GetProcessId</a></td><td>
Retrieves the process identifier of the audio session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_GetSessionIdentifier">GetSessionIdentifier</a></td><td>
Retrieves the identifier for the audio session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_GetSessionInstanceIdentifier">GetSessionInstanceIdentifier</a></td><td>
Retrieves the identifier of the audio session instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_GetState">GetState</a></td><td>
Retrieves the current state of the audio session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_IsSystemSoundsSession">IsSystemSoundsSession</a></td><td>
Indicates whether the session is a system sounds session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_RegisterAudioSessionNotification">RegisterAudioSessionNotification</a></td><td>
Registers the client to receive notifications of session events, including changes in the session state.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_SetDisplayName">SetDisplayName</a></td><td>
Assigns a display name to the current audio session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_SetDuckingPreference">SetDuckingPreference</a></td><td>
Enables or disables the default stream attenuation experience (auto-ducking) provided by the system.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_SetGroupingParam">SetGroupingParam</a></td><td>
Assigns a session to a grouping of sessions.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_SetIconPath">SetIconPath</a></td><td>
Assigns a display icon to the current session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2_UnregisterAudioSessionNotification">UnregisterAudioSessionNotification</a></td><td>
Deletes a previous registration by the client to receive notifications.</td></tr></table>&nbsp;
<a href="#iaudiosessioncontrol2-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nn-audiopolicy-iaudiosessioncontrol" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nn-audiopolicy-iaudiosessioncontrol</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />