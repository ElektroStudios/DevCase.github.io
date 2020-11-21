# ISimpleAudioVolume Interface
 

Enables a client to control the master volume level of an audio session. 

 The IAudioClient.Initialize method initializes a stream object and assigns the stream to an audio session.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("87CE5498-68D6-44E5-9215-6DA47EF883D8")]
public interface ISimpleAudioVolume
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("87CE5498-68D6-44E5-9215-6DA47EF883D8")>
Public Interface ISimpleAudioVolume
```

**VB Usage**<br />
``` VB Usage
Dim instance As ISimpleAudioVolume
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"87CE5498-68D6-44E5-9215-6DA47EF883D8")]
public interface class ISimpleAudioVolume
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("87CE5498-68D6-44E5-9215-6DA47EF883D8")>]
type ISimpleAudioVolume =  interface end
```

The ISimpleAudioVolume type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISimpleAudioVolume_GetMasterVolume">GetMasterVolume</a></td><td>
Retrieves the client volume level for the audio session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISimpleAudioVolume_GetMute">GetMute</a></td><td>
Retrieves the current muting state for the audio session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISimpleAudioVolume_SetMasterVolume">SetMasterVolume</a></td><td>
Sets the master volume level for the audio session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISimpleAudioVolume_SetMute">SetMute</a></td><td>
Sets the muting state for the audio session.</td></tr></table>&nbsp;
<a href="#isimpleaudiovolume-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/audioclient/nn-audioclient-isimpleaudiovolume" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/audioclient/nn-audioclient-isimpleaudiovolume</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />