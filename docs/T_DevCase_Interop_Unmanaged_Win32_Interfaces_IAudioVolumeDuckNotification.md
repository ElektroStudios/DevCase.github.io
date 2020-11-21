# IAudioVolumeDuckNotification Interface
 

Provides notification about stream attenuation changes. Stream Attenuation, or ducking.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("C3B284D4-6D39-4359-B3CF-B56DDB3BB39C")]
public interface IAudioVolumeDuckNotification
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("C3B284D4-6D39-4359-B3CF-B56DDB3BB39C")>
Public Interface IAudioVolumeDuckNotification
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioVolumeDuckNotification
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"C3B284D4-6D39-4359-B3CF-B56DDB3BB39C")]
public interface class IAudioVolumeDuckNotification
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("C3B284D4-6D39-4359-B3CF-B56DDB3BB39C")>]
type IAudioVolumeDuckNotification =  interface end
```

The IAudioVolumeDuckNotification type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioVolumeDuckNotification_OnVolumeDuckNotification">OnVolumeDuckNotification</a></td><td>
Sends a notification about a pending system ducking event.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioVolumeDuckNotification_OnVolumeUnduckNotification">OnVolumeUnduckNotification</a></td><td>
Sends a notification about a pending system unducking event.</td></tr></table>&nbsp;
<a href="#iaudiovolumeducknotification-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nn-audiopolicy-iaudiovolumeducknotification" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nn-audiopolicy-iaudiovolumeducknotification</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />