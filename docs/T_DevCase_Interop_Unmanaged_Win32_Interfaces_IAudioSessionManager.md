# IAudioSessionManager Interface
 

Enables a client to access the session controls and volume controls for both cross-process and process-specific audio sessions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("BFA971F1-4D5E-40BB-935E-967039BFBEE4")]
public interface IAudioSessionManager
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("BFA971F1-4D5E-40BB-935E-967039BFBEE4")>
Public Interface IAudioSessionManager
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionManager
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"BFA971F1-4D5E-40BB-935E-967039BFBEE4")]
public interface class IAudioSessionManager
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("BFA971F1-4D5E-40BB-935E-967039BFBEE4")>]
type IAudioSessionManager =  interface end
```

The IAudioSessionManager type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager_GetAudioSessionControl">GetAudioSessionControl</a></td><td>
Retrieves an audio session control.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager_GetSimpleAudioVolume">GetSimpleAudioVolume</a></td><td>
Retrieves a simple audio volume control.</td></tr></table>&nbsp;
<a href="#iaudiosessionmanager-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nn-audiopolicy-iaudiosessionmanager" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nn-audiopolicy-iaudiosessionmanager</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />