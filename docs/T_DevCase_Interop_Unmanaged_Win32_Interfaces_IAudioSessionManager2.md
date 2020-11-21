# IAudioSessionManager2 Interface
 

Enables an application to manage submixes for the audio device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("77AA99A0-1BD6-484F-8BC7-2C654C9A9B6F")]
public interface IAudioSessionManager2
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("77AA99A0-1BD6-484F-8BC7-2C654C9A9B6F")>
Public Interface IAudioSessionManager2
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionManager2
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"77AA99A0-1BD6-484F-8BC7-2C654C9A9B6F")]
public interface class IAudioSessionManager2
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("77AA99A0-1BD6-484F-8BC7-2C654C9A9B6F")>]
type IAudioSessionManager2 =  interface end
```

The IAudioSessionManager2 type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager2_GetAudioSessionControl">GetAudioSessionControl</a></td><td>
Retrieves an audio session control.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager2_GetSessionEnumerator">GetSessionEnumerator</a></td><td>
Gets a pointer to the audio session enumerator object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager2_GetSimpleAudioVolume">GetSimpleAudioVolume</a></td><td>
Retrieves a simple audio volume control.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager2_RegisterDuckNotification">RegisterDuckNotification</a></td><td>
Registers the application with the session manager to receive ducking notifications.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager2_RegisterSessionNotification">RegisterSessionNotification</a></td><td>
Registers the application to receive a notification when a session is created.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager2_UnregisterDuckNotification">UnregisterDuckNotification</a></td><td>
Deletes a previous registration by the application to receive notifications.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager2_UnregisterSessionNotification">UnregisterSessionNotification</a></td><td>
Deletes the registration to receive a notification when a session is created.</td></tr></table>&nbsp;
<a href="#iaudiosessionmanager2-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nn-audiopolicy-iaudiosessionmanager2" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nn-audiopolicy-iaudiosessionmanager2</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />