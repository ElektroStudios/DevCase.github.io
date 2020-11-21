# IAudioSessionEvents Interface
 

Provides notifications of session-related events such as changes in the volume level, display name, and session state. 

 Unlike the other interfaces in this section, which are implemented by the WASAPI system component, a WASAPI client implements the IAudioSessionEvents interface. 

 To receive event notifications, the client passes a pointer to its IAudioSessionEvents interface to the <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl_RegisterAudioSessionNotification">RegisterAudioSessionNotification(IAudioSessionEvents)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("24918ACC-64B3-37C1-8CA9-74A66E9957A8")]
public interface IAudioSessionEvents
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("24918ACC-64B3-37C1-8CA9-74A66E9957A8")>
Public Interface IAudioSessionEvents
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionEvents
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"24918ACC-64B3-37C1-8CA9-74A66E9957A8")]
public interface class IAudioSessionEvents
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("24918ACC-64B3-37C1-8CA9-74A66E9957A8")>]
type IAudioSessionEvents =  interface end
```

The IAudioSessionEvents type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents_OnChannelVolumeChanged">OnChannelVolumeChanged</a></td><td>
Notifies the client that the volume level of an audio channel in the session submix has changed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents_OnDisplayNameChanged">OnDisplayNameChanged</a></td><td>
Notifies the client that the display name for the session has changed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents_OnGroupingParamChanged">OnGroupingParamChanged</a></td><td>
Notifies the client that the grouping parameter for the session has changed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents_OnIconPathChanged">OnIconPathChanged</a></td><td>
Notifies the client that the display icon for the session has changed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents_OnSessionDisconnected">OnSessionDisconnected</a></td><td>
Notifies the client that the session has been disconnected.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents_OnSimpleVolumeChanged">OnSimpleVolumeChanged</a></td><td>
Notifies the client that the volume level or muting state of the session has changed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents_OnStateChanged">OnStateChanged</a></td><td>
Notifies the client that the stream-activity state of the session has changed.</td></tr></table>&nbsp;
<a href="#iaudiosessionevents-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nn-audiopolicy-iaudiosessionevents" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nn-audiopolicy-iaudiosessionevents</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />